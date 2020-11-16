<template>
  <div class="homepage">
    <div class="homepage__container">
      <div class="frame">
        <div class="home">
          <img src="@/assets/images/cover-elements/cover-frame.png" alt="Young Planet | Dog Days" />
          <div class="home-cover" :class="{hideHome : !showHome}">
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
          <div class="credits-cover" :class="{show : showCredits}">
            <h1 class="cidida" :class="{show : showCidida}">This is the Cidida</h1>
            <h1 class="july" :class="{show : showJuly}">This is the July</h1>
            <h1 class="pj" :class="{show : showPj}">This is the Pj</h1>
            <h1 class="dallas" :class="{show : showDallas}">This is the Dallas</h1>
            <h1 class="mitch" :class="{show : showMitch}">This is the Mitch</h1>
            <h1 class="joe" :class="{show : showJoe}">This is the Joe</h1>
          </div>
          <div class="listen-cover" :class="{show : showListen}">
            <h1>This is the Listen page</h1>
          </div>
          <div class="download-cover" :class="{show : showDownload}">
            <h1>This is the Download page</h1>
          </div>
          <div class="contact-cover" :class="{show : showContact}">
            <h1>This is the Contact page</h1>
          </div>
        </div>
      </div>
      <div class="control-panel">
        <div class="buttons">
          <button @click="listenToggle">Listen</button>
          <button @click="downloadToggle">Download</button>
          <button @click="creditsToggle">Credits</button>
          <button @click="contactToggle">Contact</button>
        </div>
        <div class="screen">
          <div class="credits" :class="{active : showCredits}">
            <div class="credits__artist" @click="cididaToggle">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Cidida</p>
            </div>
            <div class="credits__artist" @click="julyToggle">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>July Porter</p>
            </div>
            <div class="credits__artist" @click="pjToggle">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>PJ Katz</p>
            </div>
            <div class="credits__artist" @click="dallasToggle">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Dallas James</p>
            </div>
            <div class="credits__artist" @click="joeToggle">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Joe Lambert</p>
            </div>
            <div class="credits__artist" @click="mitchToggle">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" alt="Young Planet x PJ Katz | Dog Days" />
              </div>
              <p>Mitch</p>
            </div>
          </div>
          <div class="listen" :class="{show : showListen}">
            <div class="listen__platform">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
            </div>
          </div>
          <div class="download" :class="{show : showDownload}">
            <div class="download__platform">
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
              <div class="image">
                <img src="@/assets/images/placeholder.jpg" />
              </div>
            </div>
          </div>
          <div class="contact" :class="{show : showContact}">
            <div class="contact__platform">
              <div class="link">
                <h1>Instagram</h1>
                <h1>Instagram</h1>
                <h1>Instagram</h1>
              </div>
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
      showHome: true,
      showCredits: false,
      showDownload: false,
      showListen: false,
      showContact: false,
      showCidida: false,
      showJuly: false,
      showPj: false,
      showDallas: false,
      showMitch: false,
      showJoe: false
    }
  },
  methods: {
    creditsToggle() {
      this.showCredits = true
      this.showHome = false
      this.showListen = false
      this.showDownload = false
      this.showContact = false
    },
    listenToggle() {
      this.showListen = true
      this.showCredits = false
      this.showHome = false
      this.showDownload = false
      this.showContact = false
    },
    downloadToggle() {
      this.showDownload = true
      this.showListen = false
      this.showCredits = false
      this.showHome = false
      this.showContact = false
    },
    contactToggle() {
      this.showContact = true
      this.showDownload = false
      this.showListen = false
      this.showCredits = false
      this.showHome = false
    },
    cididaToggle() {
      this.showCidida = true
      this.showJuly = false
      this.showPj = false
      this.showDallas = false
      this.showMitch = false
      this.showJoe = false
    },
    cididaToggle() {
      this.showCidida = true
      this.showJuly = false
      this.showPj = false
      this.showDallas = false
      this.showMitch = false
      this.showJoe = false
    },
    julyToggle() {
      this.showJuly = true
      this.showCidida = false
      this.showPj = false
      this.showDallas = false
      this.showMitch = false
      this.showJoe = false
    },
    pjToggle() {
      this.showPj = true
      this.showCidida = false
      this.showJuly = false
      this.showDallas = false
      this.showMitch = false
      this.showJoe = false
    },
    dallasToggle() {
      this.showDallas = true
      this.showCidida = false
      this.showJuly = false
      this.showPj = false
      this.showMitch = false
      this.showJoe = false
    },
    mitchToggle() {
      this.showMitch = true
      this.showCidida = false
      this.showJuly = false
      this.showPj = false
      this.showDallas = false
      this.showJoe = false
    },
    joeToggle() {
      this.showJoe = true
      this.showCidida = false
      this.showJuly = false
      this.showPj = false
      this.showDallas = false
      this.showMitch = false
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../sass/_homepage.scss"
</style>
