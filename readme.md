# A shopping cart using jQuery with sessionStorage

[![Netlify Status](https://api.netlify.com/api/v1/badges/e7e9abaa-bbe7-49dd-badd-ce47216dc219/deploy-status)](https://app.netlify.com/sites/shoppingcartexample/deploys)

You can see a demo of the shopping cart by clicking on any of the following two links:
- https://shoppingcartexample.netlify.com  
- https://danielcregg.github.io/shoppingcart/

This shopping cart is built using jQuery and sessionStorage. It also includes PayPal payments. This is a proof-of-concept and is not intended to replace any existing server-side techniques. 

Bear in mind that there are a few things you need to change on the main `jquery.shop.js` file, namely:

* The type of PayPal's cart.
* Your business email address.
* The URL of the PayPal's form.
* The way shipping charges are calculated.
