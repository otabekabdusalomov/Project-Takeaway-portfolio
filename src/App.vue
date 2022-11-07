<template>
  <the-nav></the-nav>
  <the-home></the-home>
  <the-products></the-products>
  <the-works></the-works>
  <the-menu></the-menu>
  <the-order></the-order>
  <the-call></the-call>
  <the-support></the-support>
  <the-footer></the-footer>
</template>
<script>
import TheNav from "./components/TheNav.vue";
import TheHome from "./views/Home.vue";
import TheProducts from "./views/TheProducts.vue";
import TheWorks from "./views/TheWorks.vue";
import TheMenu from "./views/TheMenu.vue";
import TheOrder from "./views/TheOrder.vue";
import TheCall from "./views/TheCall.vue";
import TheSupport from "./views/TheSupport.vue";
import TheFooter from "./views/TheFooter.vue";
import "./css/app.css";
export default {
  components: {
    TheNav,
    TheHome,
    TheProducts,
    TheWorks,
    TheMenu,
    TheOrder, 
    TheCall,
    TheSupport,
    TheFooter
  },
};
</script>
