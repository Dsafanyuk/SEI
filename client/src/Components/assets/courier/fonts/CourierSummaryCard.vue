<template>
  <div class="row">
    <div class="col-lg-4">
      <div class="card-box">
        <div class="bar-widget">
          <div class="table-box">
            <div class="table-detail">
              <div class="iconbox bg-info">
                <i class="mdi mdi-shopping"></i>
              </div>
            </div>

            <div class="table-detail">
              <h4 class="m-t-0 m-b-5">
                <b>{{available_orders}}</b>
              </h4>
              <p class="text-muted m-b-0 m-t-0">Total Available Orders</p>
            </div>
            <div class="table-detail text-right">
              <span
                data-plugin="peity-bar"
                data-colors="#34d3eb,#ebeff2"
                data-width="120"
                data-height="45"
                style="display: none;"
              >5,3,9,6,5,9,7,3,5,2,9,7,2,1</span>
              <svg class="peity" height="45" width="120">
                <rect
                  fill="#34d3eb"
                  x="0.8571428571428571"
                  y="20"
                  width="6.857142857142858"
                  height="25"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="9.428571428571429"
                  y="30"
                  width="6.857142857142856"
                  height="15"
                ></rect>
                <rect fill="#34d3eb" x="18" y="0" width="6.857142857142858" height="45"></rect>
                <rect
                  fill="#ebeff2"
                  x="26.571428571428573"
                  y="15"
                  width="6.857142857142858"
                  height="30"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="35.14285714285714"
                  y="20"
                  width="6.857142857142861"
                  height="25"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="43.714285714285715"
                  y="0"
                  width="6.857142857142854"
                  height="45"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="52.285714285714285"
                  y="10"
                  width="6.857142857142861"
                  height="35"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="60.857142857142854"
                  y="30"
                  width="6.857142857142854"
                  height="15"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="69.42857142857143"
                  y="20"
                  width="6.857142857142861"
                  height="25"
                ></rect>
                <rect fill="#ebeff2" x="78" y="35" width="6.857142857142861" height="10"></rect>
                <rect
                  fill="#34d3eb"
                  x="86.57142857142857"
                  y="0"
                  width="6.857142857142861"
                  height="45"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="95.14285714285714"
                  y="10"
                  width="6.857142857142861"
                  height="35"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="103.71428571428571"
                  y="35"
                  width="6.857142857142861"
                  height="10"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="112.28571428571429"
                  y="40"
                  width="6.857142857142847"
                  height="5"
                ></rect>
              </svg>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Ban 2 -->
    <div class="col-lg-4">
      <div class="card-box">
        <div class="bar-widget">
          <div class="table-box">
            <div class="table-detail">
              <div class="iconbox bg-info">
                <i class="mdi mdi-shopping"></i>
              </div>
            </div>

            <div class="table-detail">
              <h4 class="m-t-0 m-b-5">
                <b>{{delivered_orders}}</b>
              </h4>
              <p class="text-muted m-b-0 m-t-0">Total Delivered Orders</p>
            </div>
            <div class="table-detail text-right">
              <span
                data-plugin="peity-bar"
                data-colors="#34d3eb,#ebeff2"
                data-width="120"
                data-height="45"
                style="display: none;"
              >5,3,9,6,5,9,7,3,5,2,9,7,2,1</span>
              <svg class="peity" height="45" width="120">
                <rect
                  fill="#34d3eb"
                  x="0.8571428571428571"
                  y="20"
                  width="6.857142857142858"
                  height="25"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="9.428571428571429"
                  y="30"
                  width="6.857142857142856"
                  height="15"
                ></rect>
                <rect fill="#34d3eb" x="18" y="0" width="6.857142857142858" height="45"></rect>
                <rect
                  fill="#ebeff2"
                  x="26.571428571428573"
                  y="15"
                  width="6.857142857142858"
                  height="30"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="35.14285714285714"
                  y="20"
                  width="6.857142857142861"
                  height="25"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="43.714285714285715"
                  y="0"
                  width="6.857142857142854"
                  height="45"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="52.285714285714285"
                  y="10"
                  width="6.857142857142861"
                  height="35"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="60.857142857142854"
                  y="30"
                  width="6.857142857142854"
                  height="15"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="69.42857142857143"
                  y="20"
                  width="6.857142857142861"
                  height="25"
                ></rect>
                <rect fill="#ebeff2" x="78" y="35" width="6.857142857142861" height="10"></rect>
                <rect
                  fill="#34d3eb"
                  x="86.57142857142857"
                  y="0"
                  width="6.857142857142861"
                  height="45"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="95.14285714285714"
                  y="10"
                  width="6.857142857142861"
                  height="35"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="103.71428571428571"
                  y="35"
                  width="6.857142857142861"
                  height="10"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="112.28571428571429"
                  y="40"
                  width="6.857142857142847"
                  height="5"
                ></rect>
              </svg>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Ban 3 -->
    <div class="col-lg-4">
      <div class="card-box">
        <div class="bar-widget">
          <div class="table-box">
            <div class="table-detail">
              <div class="iconbox bg-info">
                <i class="mdi mdi-shopping"></i>
              </div>
            </div>

            <div class="table-detail">
              <h4 class="m-t-0 m-b-5">
                <b>{{revenue}}</b>
              </h4>
              <p class="text-muted m-b-0 m-t-0">Total Revenue</p>
            </div>
            <div class="table-detail text-right">
              <span
                data-plugin="peity-bar"
                data-colors="#34d3eb,#ebeff2"
                data-width="120"
                data-height="45"
                style="display: none;"
              >5,3,9,6,5,9,7,3,5,2,9,7,2,1</span>
              <svg class="peity" height="45" width="120">
                <rect
                  fill="#34d3eb"
                  x="0.8571428571428571"
                  y="20"
                  width="6.857142857142858"
                  height="25"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="9.428571428571429"
                  y="30"
                  width="6.857142857142856"
                  height="15"
                ></rect>
                <rect fill="#34d3eb" x="18" y="0" width="6.857142857142858" height="45"></rect>
                <rect
                  fill="#ebeff2"
                  x="26.571428571428573"
                  y="15"
                  width="6.857142857142858"
                  height="30"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="35.14285714285714"
                  y="20"
                  width="6.857142857142861"
                  height="25"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="43.714285714285715"
                  y="0"
                  width="6.857142857142854"
                  height="45"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="52.285714285714285"
                  y="10"
                  width="6.857142857142861"
                  height="35"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="60.857142857142854"
                  y="30"
                  width="6.857142857142854"
                  height="15"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="69.42857142857143"
                  y="20"
                  width="6.857142857142861"
                  height="25"
                ></rect>
                <rect fill="#ebeff2" x="78" y="35" width="6.857142857142861" height="10"></rect>
                <rect
                  fill="#34d3eb"
                  x="86.57142857142857"
                  y="0"
                  width="6.857142857142861"
                  height="45"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="95.14285714285714"
                  y="10"
                  width="6.857142857142861"
                  height="35"
                ></rect>
                <rect
                  fill="#34d3eb"
                  x="103.71428571428571"
                  y="35"
                  width="6.857142857142861"
                  height="10"
                ></rect>
                <rect
                  fill="#ebeff2"
                  x="112.28571428571429"
                  y="40"
                  width="6.857142857142847"
                  height="5"
                ></rect>
              </svg>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Start of Recent Order -->
  </div>
</template>

<script>
import axios from "../../../axios";
import browserCookies from "browser-cookies";
import Toasted from "vue-toasted";
const user = browserCookies.get("user_id");

export default {
  name: "CourierOrderSummary",
  props: {
    productID: Number
  },
  data() {
    return {
      available_orders: 0,
      delivered_orders: 0,
      revenue: 0
    };
  },
  methods: {
    getAvailableOrders() {
      axios
        .get("/api/courier/" + user + "/countAvailableOrder")
        .then(response => {
          this.available_orders = response.data[0][0]["count_av"];
        });
    },
    getTotalDelivered() {
      axios
        .get("/api/courier/" + user + "/getTotalDelivered")
        .then(response => {
          this.delivered_orders = response.data[0][0]["count_d"];
        });
    },
    getRevenue() {
      axios.get("/api/courier/" + user + "/getRevenue").then(response => {
        this.revenue = response.data[0][0]["revenue"];
      });
    }
  },

  mounted: function() {
    this.getAvailableOrders();
    this.getTotalDelivered();
    this.getRevenue();
  }
};
</script>

<style scoped="true">
@import "../../assets/courier/css/core.scss";

</style>
