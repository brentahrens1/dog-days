<template>
  <div class="homepage">
    <div class="homepage__container">
      <div class="frame">
        <div class="image">
          <img src="@/assets/images/cover-elements/cover-frame.png" alt="Young Planet | Dog Days" />
        </div>
        <div class="background-elements">
          <div class="background-image">
            <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet | Dog Days EP" />
          </div>
          <div class="car">
            <img src="@/assets/images/cover-elements/car.png" alt="Young Planet | Dog Days EP Out Now" />
          </div>
          <div class="tree">
            <img src="@/assets/images/cover-elements/tree.png" alt="Young Planet | Dog Days Available on all platforms" />
          </div>
          <div class="cloud1">
            <img src="@/assets/images/cover-elements/cloud1.png" alt="Young Planet | Dog Days Available on all platforms" />
          </div>
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
