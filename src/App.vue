<template>
  <div id="app">
    <header
      class="d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3 bg-body border-bottom shadow-sm"
    >
      <p class="h3 my-0 me-md-auto fw-normal">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          fill="currentColor"
          class="bi bi-shop"
          viewBox="0 0 16 16"
        >
          <path
            d="M2.97 1.35A1 1 0 0 1 3.73 1h8.54a1 1 0 0 1 .76.35l2.609 3.044A1.5 1.5 0 0 1 16 5.37v.255a2.375 2.375 0 0 1-4.25 1.458A2.371 2.371 0 0 1 9.875 8 2.37 2.37 0 0 1 8 7.083 2.37 2.37 0 0 1 6.125 8a2.37 2.37 0 0 1-1.875-.917A2.375 2.375 0 0 1 0 5.625V5.37a1.5 1.5 0 0 1 .361-.976l2.61-3.045zm1.78 4.275a1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0 1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0 1.375 1.375 0 1 0 2.75 0V5.37a.5.5 0 0 0-.12-.325L12.27 2H3.73L1.12 5.045A.5.5 0 0 0 1 5.37v.255a1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0zM1.5 8.5A.5.5 0 0 1 2 9v6h1v-5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v5h6V9a.5.5 0 0 1 1 0v6h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1V9a.5.5 0 0 1 .5-.5zM4 15h3v-5H4v5zm5-5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-3zm3 0h-2v3h2v-3z"
          />
        </svg>
        PDShop's
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          fill="currentColor"
          class="bi bi-shop"
          viewBox="0 0 16 16"
        >
          <path
            d="M2.97 1.35A1 1 0 0 1 3.73 1h8.54a1 1 0 0 1 .76.35l2.609 3.044A1.5 1.5 0 0 1 16 5.37v.255a2.375 2.375 0 0 1-4.25 1.458A2.371 2.371 0 0 1 9.875 8 2.37 2.37 0 0 1 8 7.083 2.37 2.37 0 0 1 6.125 8a2.37 2.37 0 0 1-1.875-.917A2.375 2.375 0 0 1 0 5.625V5.37a1.5 1.5 0 0 1 .361-.976l2.61-3.045zm1.78 4.275a1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0 1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0 1.375 1.375 0 1 0 2.75 0V5.37a.5.5 0 0 0-.12-.325L12.27 2H3.73L1.12 5.045A.5.5 0 0 0 1 5.37v.255a1.375 1.375 0 0 0 2.75 0 .5.5 0 0 1 1 0zM1.5 8.5A.5.5 0 0 1 2 9v6h1v-5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v5h6V9a.5.5 0 0 1 1 0v6h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1V9a.5.5 0 0 1 .5-.5zM4 15h3v-5H4v5zm5-5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-3zm3 0h-2v3h2v-3z"
          />
        </svg>
      </p>
      <a class="btn btn-outline-danger"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          fill="currentColor"
          class="bi bi-bag-check-fill"
          viewBox="0 0 16 16"
        >
          <path
            fill-rule="evenodd"
            d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0zm-.646 5.354a.5.5 0 0 0-.708-.708L7.5 10.793 6.354 9.646a.5.5 0 1 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0l3-3z"
          />
        </svg>
        จำนวน
        {{
          product1.amount +
          product2.amount +
          product3.amount +
          product4.amount +
          product5.amount +
          product6.amount
        }}
        ชุด
      </a>
    </header>
    <main class="container">
      <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
        <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
          <div class="col">
            <div class="card mb-4 shadow-sm">
              <div class="card-header">
                <h4 class="my-0 fw-normal">{{ product1.name }}</h4>
              </div>
              <div class="card-body">
                <img
                  src="https://cf.shopee.co.th/file/f5c9697d997400b036a38be117b88fce"
                  width="100%"
                  height="100%"
                />
                <ul class="list-unstyled text-small">
                  59 บาท
                </ul>
                <div id="example-1">
                  <button
                    type="button"
                    class="w-100 btn btn-outline-danger"
                    v-on:click="product1.amount += 1"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-bag-plus-fill"
                      viewBox="0 0 16 16"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0zM8.5 8a.5.5 0 0 0-1 0v1.5H6a.5.5 0 0 0 0 1h1.5V12a.5.5 0 0 0 1 0v-1.5H10a.5.5 0 0 0 0-1H8.5V8z"
                      />
                    </svg>
                    เพิ่มชุดนอน
                  </button>
                  <p>จำนวน {{ product1.amount }} ชุด</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card mb-4 shadow-sm">
              <div class="card-header">
                <h4 class="my-0 fw-normal">{{ product2.name }}</h4>
              </div>
              <div class="card-body">
                <img
                  src="https://cf.shopee.co.th/file/37f5112f2d48a862fc238e24e6c311c7"
                  width="100%"
                  height="100%"
                />
                <ul class="list-unstyled text-small">
                  99 บาท
                </ul>
                <div id="example-2">
                  <button
                    type="button"
                    class="w-100 btn btn-outline-danger"
                    v-on:click="product2.amount += 1"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-bag-plus-fill"
                      viewBox="0 0 16 16"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0zM8.5 8a.5.5 0 0 0-1 0v1.5H6a.5.5 0 0 0 0 1h1.5V12a.5.5 0 0 0 1 0v-1.5H10a.5.5 0 0 0 0-1H8.5V8z"
                      />
                    </svg>
                    เพิ่มชุดนอน
                  </button>
                  <p>จำนวน {{ product2.amount }} ชุด</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card mb-4 shadow-sm">
              <div class="card-header">
                <h4 class="my-0 fw-normal">{{ product3.name }}</h4>
              </div>
              <div class="card-body">
                <img
                  src="https://cf.shopee.co.th/file/7e636acb2a90a0be287b3bcee1d3058d"
                  width="100%"
                  height="100%"
                />
                <ul class="list-unstyled text-small">
                  49 บาท
                </ul>
                <div id="example-3">
                  <button
                    type="button"
                    class="w-100 btn btn-outline-danger"
                    v-on:click="product3.amount += 1"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-bag-plus-fill"
                      viewBox="0 0 16 16"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0zM8.5 8a.5.5 0 0 0-1 0v1.5H6a.5.5 0 0 0 0 1h1.5V12a.5.5 0 0 0 1 0v-1.5H10a.5.5 0 0 0 0-1H8.5V8z"
                      />
                    </svg>
                    เพิ่มชุดนอน
                  </button>
                  <p>จำนวน {{ product3.amount }} ชุด</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
          <div class="col">
            <div class="card mb-4 shadow-sm">
              <div class="card-header">
                <h4 class="my-0 fw-normal">{{ product4.name }}</h4>
              </div>
              <div class="card-body">
                <img
                  src="https://cf.shopee.co.th/file/113e36ef913472de2851f33fd4331692"
                  width="100%"
                  height="100%"
                />
                <ul class="list-unstyled text-small">
                  95 บาท
                </ul>
                <div id="example-4">
                  <button
                    type="button"
                    class="w-100 btn btn-outline-danger"
                    v-on:click="product4.amount += 1"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-bag-plus-fill"
                      viewBox="0 0 16 16"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0zM8.5 8a.5.5 0 0 0-1 0v1.5H6a.5.5 0 0 0 0 1h1.5V12a.5.5 0 0 0 1 0v-1.5H10a.5.5 0 0 0 0-1H8.5V8z"
                      />
                    </svg>
                    เพิ่มชุดนอน
                  </button>
                  <p>จำนวน {{ product4.amount }} ชุด</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card mb-4 shadow-sm">
              <div class="card-header">
                <h4 class="my-0 fw-normal">{{ product5.name }}</h4>
              </div>
              <div class="card-body">
                <img
                  src="https://cf.shopee.co.th/file/5ea9f2aba7f13a24b30d0585cdac2cf7"
                  width="100%"
                  height="100%"
                />
                <ul class="list-unstyled text-small">
                  31 บาท
                </ul>
                <div id="example-5">
                  <button
                    type="button"
                    class="w-100 btn btn-outline-danger"
                    v-on:click="product5.amount += 1"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-bag-plus-fill"
                      viewBox="0 0 16 16"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0zM8.5 8a.5.5 0 0 0-1 0v1.5H6a.5.5 0 0 0 0 1h1.5V12a.5.5 0 0 0 1 0v-1.5H10a.5.5 0 0 0 0-1H8.5V8z"
                      />
                    </svg>
                    เพิ่มชุดนอน
                  </button>
                  <p>จำนวน {{ product5.amount }} ชุด</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="card mb-4 shadow-sm">
              <div class="card-header">
                <h4 class="my-0 fw-normal">{{ product6.name }}</h4>
              </div>
              <div class="card-body">
                <img
                  src="https://cf.shopee.co.th/file/d8473b59fe36fb83be3a439ffaf024d5"
                  width="100%"
                  height="100%"
                />
                <ul class="list-unstyled text-small">
                  82 บาท
                </ul>
                <div id="example-6">
                  <button
                    type="button"
                    class="w-100 btn btn-outline-danger"
                    v-on:click="product6.amount += 1"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-bag-plus-fill"
                      viewBox="0 0 16 16"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M10.5 3.5a2.5 2.5 0 0 0-5 0V4h5v-.5zm1 0V4H15v10a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4h3.5v-.5a3.5 3.5 0 1 1 7 0zM8.5 8a.5.5 0 0 0-1 0v1.5H6a.5.5 0 0 0 0 1h1.5V12a.5.5 0 0 0 1 0v-1.5H10a.5.5 0 0 0 0-1H8.5V8z"
                      />
                    </svg>
                    เพิ่มชุดนอน
                  </button>
                  <p>จำนวน {{ product6.amount }} ชุด</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <p class="h4 my-0 me-md-auto fw-normal">รายการสินค้า</p>
        <header
          class="d-flex flex-column flex-md-row align-items-mide p-3 px-md-4 mb-3 bg-body border-bottom shadow-sm"
        >
          <div v-if="product1.amount >= 1">
            <img
              src="https://cf.shopee.co.th/file/f5c9697d997400b036a38be117b88fce"
              width="60"
              height="“60”"
            />
            <p1> x{{ product1.amount }} </p1>
          </div>
          <div v-if="product2.amount >= 1">
            <img
              src="https://cf.shopee.co.th/file/37f5112f2d48a862fc238e24e6c311c7"
              width="60"
              height="“60”"
            />
            <p1> x{{ product2.amount }}</p1>
          </div>
          <div v-if="product3.amount >= 1">
            <img
              src="https://cf.shopee.co.th/file/7e636acb2a90a0be287b3bcee1d3058d"
              width="60"
              height="“60”"
            />
            <p1> x{{ product3.amount }}</p1>
          </div>
          <div v-if="product4.amount >= 1">
            <img
              src="https://cf.shopee.co.th/file/113e36ef913472de2851f33fd4331692"
              width="60"
              height="“60”"
            />
            <p1> x{{ product4.amount }}</p1>
          </div>
          <div v-if="product5.amount >= 1">
            <img
              src="https://cf.shopee.co.th/file/5ea9f2aba7f13a24b30d0585cdac2cf7"
              width="60"
              height="“60”"
            />
            <p1> x{{ product5.amount }}</p1>
          </div>
          <div v-if="product6.amount >= 1">
            <img
              src="https://cf.shopee.co.th/file/d8473b59fe36fb83be3a439ffaf024d5"
              width="60"
              height="“60”"
            />
            <p1> x{{ product6.amount }}</p1>
          </div>
        </header>
        <h4>
          ราคารวม
          {{
            sum +
            product1.amount * product1.price +
            product2.amount * product2.price +
            product3.amount * product3.price +
            product4.amount * product4.price +
            product5.amount * product5.price +
            product6.amount * product6.price
          }}
          บาท
        </h4>
        <button
          type="button"
          class="w-50 btn btn-outline-danger"
          v-on:click="say('สั่งซื้อชุดนอนเรียบร้อย')"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-bag-fill"
            viewBox="0 0 16 16"
          >
            <path
              d="M8 1a2.5 2.5 0 0 1 2.5 2.5V4h-5v-.5A2.5 2.5 0 0 1 8 1zm3.5 3v-.5a3.5 3.5 0 1 0-7 0V4H1v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4h-3.5z"
            />
          </svg>
          สั่งซื้อ
        </button>
        <input
          type="button"
          value="Reset"
          class="w-10 btn btn-outline-warning"
          onClick="javascript:location.reload();"
        />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      product1: {
        name: "ชุดนอนไอติมชมพู",
        price: 59,
        amount: 0,
      },
      product2: {
        name: "ชุดนอนเดรส ครีมแอปปเปิ้ล",
        price: 99,
        amount: 0,
      },
      product3: {
        name: "ชุดนอนสไตล์มินิมอล",
        price: 49,
        amount: 0,
      },
      product4: {
        name: "ชุดนอนผ้าฝ้าย",
        price: 95,
        amount: 0,
      },
      product5: {
        name: "ชุดนอนโปร่งแสง",
        price: 31,
        amount: 0,
      },
      product6: {
        name: "ชุดนอนผ้าไหม",
        price: 82,
        amount: 0,
      },
      sum: 0,
      count: 0,
      say: function (message) {
        alert(message);
      },
    };
  },
};
</script>
