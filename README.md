# ShoppingCartFinal
Hub of the Shopping Cart Final for Rama.


<html>
<head>
  <title>Shopping cart</title>
  <style>
  body { 
    font-size: 16px;
    line-height: 1.5;
    font-weight: 450;
    font-family: "Helvetica Neue", sans-serif;
    background-image: url("https://i1.wp.com/mychronicdreams.com/wp-content/uploads/2017/11/krystian-tambur-101317.jpg?fit=4000%2C3000&ssl=1");
   
    font-style: normal;
    text-align: center;
}

.title {
    font-size: 40px;
    line-height: 2;
    font-weight: 500;
    font-family: "Calibri", sans-serif;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    font-style: normal;
    padding: 20px;
}

.product {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #6EE0FF;
    padding: 20px;
}

.productImg {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    padding: 20px;
}

.productDetails {
    font-size: 17px;
    line-height: 2;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
  
}

.productElement {
    font-size: 20px;
    line-height: 1.5;
    font-weight: 450;
    background-color: #fff;
    border: 5px;
    border-color: #A4E6FF;
    border-style: dotted;
    border-radius: 5px;
    background-color: #BFABFD;
    font-style: normal;
    padding: 20px;
}

.productDesc {
    background-color: #fff;
    border: 5px;
    border-color: #A4E6FF;
    border-style: dotted;
    border-radius: 5px;
    padding: 20px;
}

.productPrice {
  font-size: 18px;
    line-height: 2;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
  
}

.productQuantity {
    font-size: 18px;
    line-height: 2;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
}

.productRemoval {
    font-size: 16px;
    line-height: 1.5;
    font-weight: 450;
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    color: #333;
    font-style: normal;
    padding: 20px;
}

.productLinePrice {
  border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E8E1FF;
    padding: 20px;
}

.totals {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #E9FFC8;
    padding: 20px;
}

.totalItem {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #D6FFC6;
    padding: 20px;
}


.productTotal {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #fff;
    padding: 20px;
}


.totalValue {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #C8EFFF;
    padding: 20px;
}

.itemTotals {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #89DDFF;
    padding: 20px;
}

.removeProduct {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #78FFCA;
    padding: 20px;
}

.checkout {
    border: 2px;
    border-color: #A4E6FF;
    border-style: solid;
    border-radius: 5px;
    background-color: #78FFCA;
    padding: 20px;
}
</head>
<body>
  <h1 class="title">
    Shopping Cart
  </h1>
 
<div class="bigCart">

  <div class="columnLabels">
  
    <span class="productImg">Image</span>

    <span class="productDetails">Product</span>

    <span class="productPrice">Price</span>

    <span class="productQuantity">Quantity</span>

    <span class="productRemoval">Remove</span>

    <span class="productLinePrice">Total</span>
  </div>

  <div class="product">
    <div class="productImg">
      <img src="https://media.tnh.me/54ec061c5ccacf5872264eac/551875c75ccacf1b8200b49c" height="400" width="400">
    </div>
    <div class="productDetails">
      <div class="productElement">Futuristic Jellyfish</div>
      <p class="productDesc">Born in the past yet back from the future, this jellyfish has the ability time travel one second into the past AND future every five minutes! On top of its' cool color scheme, it's GLUTEN FREE!</p>
    </div>
    <div class="productPrice">$12.99</div>
    <div class="productQuantity">
      <input type="number" value="2" min="1">
    </div>
    <div class="productRemoval">
      <button class="removeProduct">
        Remove
      </button>
    </div>
    <div class="productLinePrice">$25.98</div>
  </div>

  <div class="product">
    <div class="productImg">
      <img src="https://vignette.wikia.nocookie.net/runescape2/images/a/a4/Durable_Jellyfish.png/revision/20150714212839" height="400" width="400">
    </div>
    <div class="productDetails">
      <div class="productElement">Android Camera Quality Jellyfish</div>
      <p class="productDesc">This potato quality jellyfish brings all the charm of a 144 pixel YouTube video, combined with the aesthetic of a terribly funded ATARI game. We don't know why people want it, but what we do know is that you will buy it.</p>
    </div>
    <div class="productPrice">$45.99</div>
    <div class="productQuantity">
      <input type="number" value="1" min="1">
    </div>
    <div class="productRemoval">
      <button class="removeProduct">
        Remove
      </button>
    </div>
    <div class="productLinePrice">$45.99</div>
  </div>


  <div class="totals">

    <div class="totalItem">
      <span>Subtotal</span>

      <div class="totalValue" id="cartSubtotal">$71.97</div>
    </div>
    <div class="totalItem">
      <span>Tax (5%)</span>

      <div class="totalValue" id="cartTax">$3.60</div>
    </div>
    <div class="totalItem">
      <span>Shipping</span>

      <div class="totalValue" id="cartShipping">$15.00</div>
    </div>

    <div class="itemTotals">
      <span>Grand Total</span>

      <div class="totalValue" id="cartTotal">$90.57</div>
    </div>
  </div>
      
      <button class="checkout">Checkout</button>

</div>

</body>
</html>
