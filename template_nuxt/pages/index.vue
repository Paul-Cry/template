<template>
  <header class="header">
    <div class="container" >
      <nav>
        <ul class="header-nav">
          <li class="header-nav-item">
            <nuxt-link to="/" class="header-nav__link">Главная</nuxt-link>
          </li>
          <li class="header-nav-item">
            <nuxt-link to="/cabinet" class="header-nav__link">Личный кабинет</nuxt-link>
          </li>
          <li class="header-nav-item" >
            <nuxt-link to="/favoriteMatch" prefetc>Избранные</nuxt-link>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>

//import { mapActions, mapGetters, mapState } from 'vuex'

export default {
  name: 'IndexPage',
  layout : 'main_layout',
  data: ()=>({
    // ...mapState({
    //   sportEvent: 'getItem/sportEvent'
    // })
  }),
  async mounted() {
    // this.$nextTick(() => {
    //   this.$nuxt.$loading.start()
    //   this.$nuxt.$loading.finish()
    // })


  },
  computed: {
    // ...mapGetters({
    //   flag: 'getItem/CloaseLoadingGet',
    // }),
  },
  methods: {
    // ...mapActions({
    //   flag: 'getItem/CloaseLoadingGet',
    // }),
  }

}
</script>


