<template>
  <v-card>
    <div v-if="this.$store.getters['courier/isLoading']">
      <v-progress-linear :indeterminate="true" height="10"></v-progress-linear>
    </div>
    <v-data-table :headers="headers" :items="orders" v-bind:pagination.sync="pagination">
      <template v-slot:no-data>
        <v-flex class="text-xs-center">
          <v-alert type="info" outline :value="true">Start accepting some orders to see them here</v-alert>
        </v-flex>
      </template>
      <template slot="items" slot-scope="props">
        <td @click="toggleDialog(props.item)">{{props.item.order_id}}</td>
        <td @click="toggleDialog(props.item)">{{props.item.first_name}}</td>
        <td @click="toggleDialog(props.item)">{{props.item.room_num}}</td>
        <td @click="toggleDialog(props.item)">{{props.item.time_created}}</td>
        <CreateConversation v-if="props.item.order_id" :order_id="parseInt(props.item.order_id)"></CreateConversation>
      </template>
    </v-data-table>
  </v-card>
</template>

<script>
import CreateConversation from "../../MainDashboard/components/ChatCreateConversation.vue";
export default {
  name: "CourierAvailableOrders",
  data() {
    return {
      pagination: { sortBy: "order_id", descending: true, rowsPerPage: 5 },
      headers: [
        { text: "Order #", align: "left", value: "order_id" },
        { text: "Name", align: "left", value: "first_name" },
        { text: "Room #", align: "left", value: "room_num" },
        { text: "Time Created", align: "left", value: "time_created" },
        { text: "", align: "left", value: "", sortable: false }
      ]
    };
  },
  props: {
    orders: Array
  },
  components: {
    CreateConversation: CreateConversation
  },
  computed: {},
  methods: {
    toggleDialog(value) {
      this.$emit("toggleSummary", value);
    }
  }
};
</script>

<style scoped lang="css">
.v-progress-linear {
  margin: auto !important;
}
</style>
