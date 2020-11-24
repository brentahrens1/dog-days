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
            <div class="background-image">
              <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet | Dog Days EP" />
            </div>
            <div class="left_tree">
              <img src="@/assets/images/edge-of-the-world/left_tree.png" alt="Young Planet | Dog Days EP" />
            </div>
            <div class="right_tree">
              <img src="@/assets/images/edge-of-the-world/right_tree.png" alt="Young Planet | Dog Days EP" />
            </div>
            <div class="cidida" :class="{show : showCidida}">
              <div class="image">
                <img src="@/assets/images/credits/page/cidida.png" alt="Cidida" />
              </div>
            </div>
            <div class="july" :class="{show : showJuly}">
              <div class="image">
                <img src="@/assets/images/credits/page/july.png" alt="Cidida" />
              </div>
            </div>
            <div class="pj" :class="{show : showPj}">
              <div class="image">
                <img src="@/assets/images/credits/page/pj.png" alt="Cidida" />
              </div>
            </div>
            <div class="dallas" :class="{show : showDallas}">
              <div class="image">
                <img src="@/assets/images/credits/thumbs/dallas-thumb.png" alt="Cidida" />
              </div>
            </div>
            <div class="mitch" :class="{show : showMitch}">
              <div class="image">
                <img src="@/assets/images/credits/page/mitch.png" alt="Cidida" />
              </div>
            </div>
            <div class="joe" :class="{show : showJoe}">
              <div class="image">
                <img src="@/assets/images/credits/page/joe.png" alt="Cidida" />
              </div>
            </div>
          </div>
          <div class="listen-cover" :class="{show : showListen}">
            <div class="edge-screen" :class="{show : showEdge}">
              <div class="background-image">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="left_tree">
                <img src="@/assets/images/edge-of-the-world/left_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="right_tree">
                <img src="@/assets/images/edge-of-the-world/right_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="mountains">
                <img src="@/assets/images/edge-of-the-world/mountains.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="water">
                <img src="@/assets/images/edge-of-the-world/water.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="truck">
                <img src="@/assets/images/edge-of-the-world/truck.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="plane">
                <img src="@/assets/images/edge-of-the-world/plane.png" alt="Young Planet | Dog Days EP" />
              </div>
            </div>
            <div class="daze-screen" :class="{show : showDaze}">
              <div class="background-image">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="left_tree">
                <img src="@/assets/images/edge-of-the-world/left_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="right_tree">
                <img src="@/assets/images/edge-of-the-world/right_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart1">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart2">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart3">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart4">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart5">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart6">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart7">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="heart8">
                <img src="@/assets/images/in-a-daze/heart.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="july-eyes">
                <img src="@/assets/images/in-a-daze/july-eyes.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="spiral-left">
                <img src="@/assets/images/in-a-daze/spiral.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="spiral-right">
                <img src="@/assets/images/in-a-daze/spiral.png" alt="Young Planet | Dog Days EP" />
              </div>
            </div>
            <div class="dog-screen" :class="{show : showDog}">
              <h1>Dog screen</h1>
            </div>
          </div>
          <div class="download-cover" :class="{show : showDownload}">
            <div class="background-image">
              <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet | Dog Days EP" />
            </div>
            <div class="hand">
                <img src="@/assets/images/download/hand.png" alt="Young Planet | Dog Days EP" />
              </div>
            <div class="phone">
                <img src="@/assets/images/download/phone.png" alt="Young Planet | Dog Days EP" />
            </div>
            <div class="left_tree">
              <img src="@/assets/images/edge-of-the-world/left_tree.png" alt="Young Planet | Dog Days EP" />
            </div>
            <div class="right_tree">
              <img src="@/assets/images/edge-of-the-world/right_tree.png" alt="Young Planet | Dog Days EP" />
            </div>
          </div>
          <div class="contact-cover" :class="{show : showContact}">
              <div class="background-image">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="left_tree">
                <img src="@/assets/images/edge-of-the-world/left_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="right_tree">
                <img src="@/assets/images/edge-of-the-world/right_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="mountains">
                <img src="@/assets/images/edge-of-the-world/mountains.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="water">
                <img src="@/assets/images/contact/thinner-water.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="plane">
                <img src="@/assets/images/contact/plane.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="crab">
                <img src="@/assets/images/contact/crab.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="thin-water">
                <img src="@/assets/images/contact/thin-water.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="bottle">
                <img src="@/assets/images/contact/bottle.png" alt="Young Planet | Dog Days EP" />
              </div>
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
              <div class="back">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image cidida">
                  <img src="@/assets/images/credits/thumbs/cidida-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Cidida</p>
            </div>
            <div class="credits__artist" @click="julyToggle">
              <div class="back">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image">
                  <img src="@/assets/images/credits/thumbs/july-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>July Porter</p>
            </div>
            <div class="credits__artist" @click="pjToggle">
              <div class="back">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image pj">
                  <img src="@/assets/images/credits/thumbs/pj-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>PJ Katz</p>
            </div>
                 <div class="credits__artist" @click="dallasToggle">
              <div class="back">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image dallas">
                  <img src="@/assets/images/credits/thumbs/dallas-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Dallas James</p>
            </div>
            <div class="credits__artist" @click="mitchToggle">
              <div class="back">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image">
                  <img src="@/assets/images/credits/thumbs/mitch-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Mitch</p>
            </div>
            <div class="credits__artist" @click="joeToggle">
              <div class="back">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image joe">
                  <img src="@/assets/images/credits/thumbs/joe-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Joe Lambert</p>
            </div>
          </div>
          <div class="listen" :class="{show : showListen}">
            <div class="listen__song">
              <div class="song-title">
                <h3 @click="edgeToggle">Edge Of The World</h3>
              </div>
              <div class="song-title">
                <h3 @click="dazeToggle">In A Daze feat. Dallas James</h3>
              </div>
              <div class="song-title">
                <h3 @click="dogToggle">Dog Days Of Summer</h3>
              </div>
            </div>
            <div class="soundcloud edge" :class="{show : showEdge}">
              <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/655015838&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/spinyoungplanet" title="Young_Planet" target="_blank" style="color: #cccccc; text-decoration: none;">Young_Planet</a> · <a href="https://soundcloud.com/spinyoungplanet/drugs" title="Drugs" target="_blank" style="color: #cccccc; text-decoration: none;">Drugs</a></div>
            </div>
            <div class="soundcloud daze" :class="{show : showDaze}">
              <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/491595693&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/spinyoungplanet" title="Young_Planet" target="_blank" style="color: #cccccc; text-decoration: none;">Young_Planet</a> · <a href="https://soundcloud.com/spinyoungplanet/celebrate-these-moments" title="Celebrate These Moments" target="_blank" style="color: #cccccc; text-decoration: none;">Celebrate These Moments</a></div>
            </div>
            <div class="soundcloud dog" :class="{show : showDog}">
              <iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/396696534&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/spinyoungplanet" title="Young_Planet" target="_blank" style="color: #cccccc; text-decoration: none;">Young_Planet</a> · <a href="https://soundcloud.com/spinyoungplanet/soldier" title="Soldier" target="_blank" style="color: #cccccc; text-decoration: none;">Soldier</a></div>
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
      showJoe: false,
      showEdge: false,
      showDaze: false,
      showDog: false
    }
  },
  methods: {
    creditsToggle() {
      this.showCredits = true
      this.showHome = false
      this.showListen = false
      this.showDownload = false
      this.showContact = false
      this.showCidida = false
      this.showJuly = false
      this.showPj = false
      this.showMitch = false
      this.showJoe = false
      this.showDallas = false
    },
    listenToggle() {
      this.showListen = true
      this.showCredits = false
      this.showHome = true
      this.showDownload = false
      this.showContact = false
      this.showEdge = false
      this.showDaze = false
      this.showDog = false
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
    edgeToggle() {
      this.showEdge = true
      this.showDaze = false
      this.showDog = false
      this.showHome = false
    },
    dazeToggle() {
      this.showDaze = true
      this.showEdge = false
      this.showDog = false
      this.showHome = false
    },
    dogToggle() {
      this.showDog = true
      this.showEdge = false
      this.showDaze = false
      this.showHome = false
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../sass/_homepage.scss"
</style>
