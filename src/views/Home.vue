<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" style="width: 100px" />
    <SvgMap src="/L1.svg" />
  </div>
</template>

<script>
// @ is an alias to /src
import SvgMap from "@/components/SvgMap.vue"
export default {
  name: 'Home',
  components: {
    SvgMap
  }
}
</script>
