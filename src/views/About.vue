<template>
  <div class="about">
    <h1>This is an about page</h1>
    <AddMap></AddMap>
  </div>
</template>
<script>
import AddMap from "../components/AddGoogleMap.vue"
export default {
  components:{
    AddMap
  },
};
</script>