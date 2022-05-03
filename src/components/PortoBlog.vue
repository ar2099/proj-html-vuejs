<template>
  <div id="porto">
      <section><img src="/images/logo-default-slim.png" alt="Logo"></section>
    
    
  </div>
</template>

<script>
export default {
  name: 'PortoBlog',
  data() {
    return {
      logo: '/images/logo-default-slim.png'
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#porto {
    background-color: rgb(255, 255, 255);
    display: flex;
    justify-content: center;
    height: 100px;
    section {
        height: 100%;
        width: 80%;
        display: flex;
        align-items: center;
    }
    img {
        height: 41%;
    }
}

</style>
