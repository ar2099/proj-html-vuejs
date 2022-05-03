<template>
  <div >
      <section>
    <span v-for="(element, index) in pannelloSopra" :key='index'><a :href="`${element.url}`">{{element.name}}</a></span>
    </section>
  </div>
</template>

<script>
export default {
  name: 'NavBlog',
  data() {
    return {
      pannelloSopra: [
        {
          name: 'HOME',
          url: '/sign-in'
        },
        {
          name: 'ELEMENTS',
          url: '/about-us'
        },
        {
          name: 'FEATURES',
          url: '/contact-us'
        },
        {
          name: 'PAGES',
          url: '/buy-now'
        },
        {
          name: 'PORTFOLIO',
          url: '/buy-now'
        },
        {
          name: 'BLOG',
          url: '/buy-now'
        },
        {
          name: 'SHOP',
          url: '/buy-now'
        },

      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
a {
    color: rgb(0, 0, 0);
    text-decoration: none;
    font-weight: bold;
}

a:hover{
    color: #0088CC;
}
span {
    margin-right: 25px;
}
div {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    border-top: 1px solid grey;
    border-bottom: 1px solid grey;
}
section {
    width: 80%;
    
}
</style>
