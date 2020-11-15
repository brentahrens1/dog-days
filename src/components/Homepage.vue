<template>
  <div class="homepage">
    <div class="homepage__container">
      <div class="frame">
        <div class="image">
          <img src="@/assets/images/cover-elements/cover-frame.png" alt="Young Planet | Dog Days" />
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
              <div class="cloud2">
                <img src="@/assets/images/cover-elements/cloud2.png" alt="Young Planet | Dog Days Available on all platforms" />
              </div>
              <div class="cloud3">
                <img src="@/assets/images/cover-elements/cloud3.png" alt="Young Planet | Dog Days Available on all platforms" />
              </div>
              <div class="cloud4">
                <img src="@/assets/images/cover-elements/cloud4.png" alt="Young Planet | Dog Days Available on all platforms" />
              </div>
              <div class="cloud5">
                <img src="@/assets/images/cover-elements/cloud5.png" alt="Young Planet | Dog Days Available on all platforms" />
              </div>
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
          <div class="credits">
            <div class="credits__artist">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Cidida</p>
            </div>
            <div class="credits__artist">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>July Porter</p>
            </div>
            <div class="credits__artist">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>PJ Katz</p>
            </div>
            <div class="credits__artist">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Dallas James</p>
            </div>
            <div class="credits__artist">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Joe Lambert</p>
            </div>
            <div class="credits__artist">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Mitch</p>
            </div>
          </div>
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
