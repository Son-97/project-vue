<template>
  <div class="header-inner">
    <div class="col-sm-4 col-xs-6 header-left">
      <div class="shipping">
        <div class="shipping-img"></div>
        <div class="shipping-text">
          (+84) 347 366 345
          <br />
          <span class="shipping-detail">24/7 Online Support</span>
        </div>
      </div>
    </div>
    <div class="col-sm-4 col-xs-12 header-middle">
      <div class="header-middle-top">
        <div id="logo">
          <a href="index.html">
            <img
              src="../assets/image/logo.png"
              title="E-Commerce"
              alt="E-Commerce"
              class="img-responsive"
            />
          </a>
        </div>
      </div>
    </div>
    <div class="col-sm-4 col-xs-12 header-right">
      <div id="cart" class="btn-group btn-block">
        <div class="btn btn-inverse btn-block cart-dropdown-button">
          <img src="../assets/image/cart.png"/>
          <div id="cart-total">
            <span class="cart-title">Shopping Cart</span>
            <br /><span>0 item(s) - $0.00</span>
          </div>
        </div>
        <ul class="dropdown-menu pull-right cart-dropdown-menu">
          <li>
            <table class="table table-striped">
              <tbody>
                <tr>
                  <td class="text-center">
                    <a href="#">
                      <img
                        class="img-thumbnail"
                        title="lorem ippsum dolor dummy"
                        alt="lorem ippsum dolor dummy"
                        src="../assets/image/product/7product50x59.jpg"
                      />
                    </a>
                  </td>
                  <td class="text-left">
                    <a href="#">lorem ippsum dolor dummy</a>
                  </td>
                  <td class="text-right">x 1</td>
                  <td class="text-right">$254.00</td>
                  <td class="text-center">
                    <button class="btn btn-danger btn-xs" title="Remove" type="button">
                      <i class="fa fa-times"></i>
                    </button>
                  </td>
                </tr>
              </tbody>
            </table>
          </li>
          <li>
            <div>
              <table class="table table-bordered">
                <tbody>
                  <tr>
                    <td class="text-right">
                      <strong>Sub-Total</strong>
                    </td>
                    <td class="text-right">$210.00</td>
                  </tr>
                  <tr>
                    <td class="text-right">
                      <strong>Eco Tax (-2.00)</strong>
                    </td>
                    <td class="text-right">$2.00</td>
                  </tr>
                  <tr>
                    <td class="text-right">
                      <strong>VAT (20%)</strong>
                    </td>
                    <td class="text-right">$42.00</td>
                  </tr>
                  <tr>
                    <td class="text-right">
                      <strong>Total</strong>
                    </td>
                    <td class="text-right">$254.00</td>
                  </tr>
                </tbody>
              </table>
              <p class="text-right">
                <span class="btn-viewcart">
                  <a href="cart.html">
                    <strong>
                      <i class="fa fa-shopping-cart"></i> View Cart
                    </strong>
                  </a>
                </span>
                <span class="btn-checkout">
                  <a href="checkout.html">
                    <strong>
                      <i class="fa fa-share"></i> Checkout
                    </strong>
                  </a>
                </span>
              </p>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>