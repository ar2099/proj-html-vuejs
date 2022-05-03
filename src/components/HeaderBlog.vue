<template>
  <div id="header">
      <section class="sopra">
          <span>Everithings about Lifestyle, Travels and Gadeget</span>
          <span v-for="(element, index) in pannelloSopra" :key='index'><a :href="`${element.url}`">{{element.name}}</a></span>
         
      </section>
  </div>
</template>

<script>
export default {
  name: 'HeaderBlog',
  data() {
    return {
      pannelloSopra: [
        {
          name: 'SIGN IN',
          url: '/sign-in'
        },
        {
          name: 'ABOUT US',
          url: '/about-us'
        },
        {
          name: 'CONTACT US',
          url: '/contact-us'
        },
        {
          name: 'BUY NOW',
          url: '/buy-now'
        },

      ]
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#header {
    background-color: #0088CC;
    display: flex;
    justify-content: center;
}
.sopra {
    background-color: #0088CC;
    height: 50px;
    display: flex;
    align-items: center;
    padding-left: 5px;
    width: 80%;
    span {
        color: white;
        margin-right: 30px;
        a {
            
            text-decoration: none;
            color: white;
        }
    }
}
</style>
