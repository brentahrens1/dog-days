<template>
  <div class="homepage">
    <div class="homepage__container">
      <div class="frame">
        <div class="image">
          <img src="@/assets/images/cover-elements/cover-frame.png" alt="Young Planet | Dog Days" />
        </div>
      </div>
      <div class="control-panel">
        <div class="buttons">
          <button>Listen</button>
          <button>Download</button>
          <button>Credits</button>
          <button>Contact</button>
        </div>
        <div class="screen">

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Homepage',
  data() {
    return {
    }
  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../sass/_homepage.scss"
</style>
