<template>

  <header class="o-header" role="banner">
    <div class="l-container">
      <a href="/" title="Katie M Fritz, LLC | Home" class="m-logo-link">
        <img src="../../assets/images/KMF-logo.svg" class="a-logo" alt="Katie M Fritz, LLC" />
      </a><!-- end a-logo -->

      <m-primary-nav/>

    </div><!-- end l-container -->
  </header><!-- end o-header -->

</template>

<script>
import mPrimaryNav from '../molecules/m-primary-nav.vue'

export default {
  data () {
    return {

    }
  },
  components: {
    'm-primary-nav': mPrimaryNav
  }
}
</script>
