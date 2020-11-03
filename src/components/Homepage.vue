<template>
  <div class="homepage">
    <div class="homepage__background">
      <img src="@/assets/images/frame.png" />
    </div>
    <div class="homepage__image-palm">
     <img src="@/assets/images/palm.png" />
    </div>
    <div class="homepage__image-chevy">
     <img src="@/assets/images/chevy.png" />
    </div>
    <div class="homepage__image" :class="{active: isVisible1}" >
     <img src="@/assets/images/biden.png" />
    </div>
    <div class="homepage__image-dance" :class="{active: isVisible2}" >
     <img src="@/assets/images/dance.png" />
    </div>
    <div class="spacer" />
  </div>
</template>

<script>
export default {
  name: 'Homepage',
  data() {
    return {
      isVisible1: false,
      isVisible2: false
    }
  },
  created () {
    window.addEventListener('scroll', this.scrolled)
    window.addEventListener('scroll', this.scrolled2)
  },
  methods: {
    scrolled() {
      if (window.scrollY > 200 && window.scrollY < 600) {
        return this.isVisible1 = true
      } else {
        return this.isVisible1 = false
      }
    },
    scrolled2() {
      if (window.scrollY > 700) {
        return this.isVisible2 = true
      } else {
        return this.isVisible2 = false
      }
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../sass/_homepage.scss"
</style>
