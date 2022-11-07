<template>
  <div class="menu">
    <h2>Browse our menu</h2>
    <p>
      Use our menu to place an order online, or phone our store to place a
      pickup order. Fast and fresh food.
    </p>
    <div class="menu_sections">
      <span>Burgers</span>
      <span>Sides</span>
      <span>Drinks</span>
    </div>
    <ul>
      <li v-for="product in products" :key="product">
        <img src="../assets/burger.png" alt="" />
        <div class="content">
          <span>
            <h3>{{ product.title }}</h3>
            <h3>{{ product.price }}</h3>
          </span>
          <p>{{ product.text }}</p>
          <span>
            <input type="number" value="1" />
            <div class="btn">Add to cart</div>
          </span>
        </div>
      </li>
    </ul>
    <div class="btn">See Full Menu</div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      products: [
        {
          title: "Burger Dreams",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
          price: "$ 9.20 USD",
        },
        {
          title: "Burger Waldo",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
          price: "$ 10.00 USD",
        },
        {
          title: "Burger Dreams",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
          price: "$ 9.20 USD",
        },
        {
          title: "Burger Waldo",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
          price: "$ 10.00 USD",
        },
        {
          title: "Burger Dreams",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
          price: "$ 9.20 USD",
        },
        {
          title: "Burger Waldo",
          text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry.",
          price: "$ 10.00 USD",
        },
      ],
    };
  },
};
</script>
