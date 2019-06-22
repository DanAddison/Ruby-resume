<template>
  <div class="layout">
    <Nav/>
    <slot/>
  </div>
</template>

<script>
import Nav from "../components/Nav";
export default {
  components: {
    Nav
  }
};
</script>


<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

<style lang="scss">
body {
  margin:0;
  padding:0;
  line-height: 1.5;
}

h3 {
  margin-bottom: 0.5rem;
}

</style>
