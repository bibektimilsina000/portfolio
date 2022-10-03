<template>
  <div class="flex"><SideBar></SideBar> <HomeComp></HomeComp></div>
</template>

<script>
import SideBar from "./components/sidebar.vue";
import HomeComp from "./components/homepage.vue";

export default {
  components: {
    SideBar,
    HomeComp,
  },
};
</script>
