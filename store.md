## Purchasing on this website

Purchasing *Python for Mechanical and Aerospace Engineering* through this website (powered by Stripe) provides the author with the greatest royalty for the same e-book price across all digital channels. If you run into any issues, email pythonforengineering (at) gmail.com!

<!-- Begin Stripe Checkout Form -->

<!-- Load Stripe.js on your website. -->
<script src="https://js.stripe.com/v3/"></script>
<link rel="stylesheet" href="css/normalize.css" />
<link rel="stylesheet" href="css/global.css" />
<section class="container">
<button data-checkout-mode="payment" data-price-id="price_1I2oiAAzc86QT0MIyKA6vxl5" class="button">Purchase for $9.99</button>
<p>(redirects to Stripe)</p>
</section>
<div id="error-message"></div>
<script>
// Replace with your own publishable key: https://dashboard.stripe.com/test/apikeys
var PUBLISHABLE_KEY = 'pk_live_51I2oSGAzc86QT0MI3vQRJs3cJGOaACRybp5nAQrVqXPoJp9r5SF3NJiR12pzTTy7AH8MpFusKMBKP6Zg6XjpvTEw00DTFyVjUX';
// Replace with the domain you want your users to be redirected back to after payment
var DOMAIN = location.href.replace(/[^/]*$/, '');


var stripe = Stripe(PUBLISHABLE_KEY);

// Handle any errors from Checkout
var handleResult = function (result) {
  if (result.error) {
     var displayError = document.getElementById('error-message');
      displayError.textContent = result.error.message;
        }
};

document.querySelectorAll('button').forEach(function (button) {
        button.addEventListener('click', function (e) {
          var mode = e.target.dataset.checkoutMode;
          var priceId = e.target.dataset.priceId;
          var items = [{ price: priceId, quantity: 1 }];

// Make the call to Stripe.js to redirect to the checkout page
// with the sku or plan ID.
stripe
            .redirectToCheckout({
              mode: mode,
              lineItems: items,
              successUrl:
                DOMAIN + 'success.html?session_id={CHECKOUT_SESSION_ID}',
              cancelUrl:
                DOMAIN + 'canceled.html?session_id={CHECKOUT_SESSION_ID}',
            })
            .then(handleResult);
        });
      });
</script>
