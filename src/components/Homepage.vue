<template>
  <div class="homepage">
    <div class="homepage__container">
      <div class="frame">
        <div class="home">
          <div class="bottom" />
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
            <div class="cidida artist" :class="{show : showCidida}">
              <div class="descripiton">
                <div class="ep">
                  <p>Dog Days</p>
                </div>
                <div class="category">
                  <p>Credits</p>
                </div>
                <div class="credit">
                  <p>Rapper Co Producer</p>
                </div>
              </div>
              <div class="image">
                <img src="@/assets/images/credits/page/cidida.png" alt="Cidida" />
              </div>
            </div>
            <div class="descripiton" :class="{show : showCidida}">
              <div class="ep">
                <p>Dog Days</p>
              </div>
              <div class="category">
                <p>Credits</p>
              </div>
              <div class="credit">
                <p>Writer Co-Producer</p>
              </div>
            </div>
            <div class="july artist" :class="{show : showJuly}">
              <div class="image">
                <img src="@/assets/images/credits/page/july.png" alt="Cidida" />
              </div>
            </div>
            <div class="descripiton" :class="{show : showJuly}">
              <div class="ep">
                <p>Dog Days</p>
              </div>
              <div class="category">
                <p>Credits</p>
              </div>
              <div class="credit">
                <p>Writer Co-Producer Mix Enginner</p>
              </div>
            </div>
            <div class="pj artist" :class="{show : showPj}">
              <div class="image">
                <img src="@/assets/images/credits/page/pj.png" alt="Cidida" />
              </div>
            </div>
            <div class="descripiton" :class="{show : showPj}">
              <div class="ep">
                <p>Dog Days</p>
              </div>
              <div class="category">
                <p>Credits</p>
              </div>
              <div class="credit">
                <p>Producer</p>
              </div>
            </div>
            <div class="dallas artist" :class="{show : showDallas}">
              <div class="image">
                <img src="@/assets/images/credits/thumbs/dallas-thumb.png" alt="Cidida" />
              </div>
            </div>
            <div class="descripiton" :class="{show : showDallas}">
              <div class="ep">
                <p>Dog Days</p>
              </div>
              <div class="category">
                <p>Credits</p>
              </div>
              <div class="credit">
                <p>Featured Artist</p>
              </div>
            </div>
            <div class="mitch artist" :class="{show : showMitch}">
              <div class="image">
                <img src="@/assets/images/credits/page/mitch.png" alt="Cidida" />
              </div>
            </div>
            <div class="descripiton" :class="{show : showMitch}">
              <div class="ep">
                <p>Dog Days</p>
              </div>
              <div class="category">
                <p>Credits</p>
              </div>
              <div class="credit">
                <p>Album Artwork</p>
              </div>
            </div>
            <div class="joe artist" :class="{show : showJoe}">
              <div class="image">
                <img src="@/assets/images/credits/page/joe.png" alt="Cidida" />
              </div>
            </div>
            <div class="descripiton" :class="{show : showJoe}">
              <div class="ep">
                <p>Dog Days</p>
              </div>
              <div class="category">
                <p>Credits</p>
              </div>
              <div class="credit">
                <p>Mastering Engineer</p>
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
              <div class="background-image">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="left_tree">
                <img src="@/assets/images/edge-of-the-world/left_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="right_tree">
                <img src="@/assets/images/edge-of-the-world/right_tree.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="dog" :class="{dogShow : dogAnimation, drag : dragOff}">
                <img src="@/assets/images/dog-days/dog.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="door">
                <img src="@/assets/images/dog-days/door.png" alt="Young Planet | Dog Days EP" />
              </div>
              <div class="news" :class="{paperShow : paperAnimation, drag : dragOff}">
                <img src="@/assets/images/dog-days/news.png" alt="Young Planet | Dog Days EP" />
              </div>
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
          <button @click="listenToggle" class="listen-btn" :class="{show : showListen}">Listen</button>
          <button @click="downloadToggle" class="download-btn" :class="{show : showDownload}">Download</button>
          <button @click="creditsToggle" class="credits-btn" :class="{show : showCredits}">Credits</button>
          <button @click="contactToggle" class="contact-btn" :class="{show : showContact}">Contact</button>
        </div>
        <div class="screen">
          <div class="logo" :class="{show : showLogo}">
              <img src="@/assets/images/icons/logo.png" alt="Young Planet x PJ Katz | Dog Days" />
          </div>
          <div class="credits" :class="{active : showCredits}">
            <div class="credits__artist" @click="cididaToggle">
              <div class="back" :class="{show : showCidida}">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image cidida">
                  <img src="@/assets/images/credits/thumbs/cidida-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Cidida</p>
            </div>
            <div class="credits__artist" @click="julyToggle">
              <div class="back" :class="{show : showJuly}">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image july">
                  <img src="@/assets/images/credits/thumbs/july-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>July Porter</p>
            </div>
            <div class="credits__artist" @click="pjToggle">
              <div class="back" :class="{show : showPj}">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image pj">
                  <img src="@/assets/images/credits/thumbs/pj-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>PJ Katz</p>
            </div>
                 <div class="credits__artist" @click="dallasToggle">
              <div class="back" :class="{show : showDallas}">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image dallas">
                  <img src="@/assets/images/credits/thumbs/dallas-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Dallas James</p>
            </div>
            <div class="credits__artist" @click="mitchToggle">
              <div class="back" :class="{show : showMitch}">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image mitch">
                  <img src="@/assets/images/credits/thumbs/mitch-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Mitch</p>
            </div>
            <div class="credits__artist" @click="joeToggle">
              <div class="back" :class="{show : showJoe}">
                <img src="@/assets/images/cover-elements/background-main.png" alt="Young Planet x PJ Katz | Dog Days" />
                <div class="image joe">
                  <img src="@/assets/images/credits/thumbs/joe-thumb.png" alt="Young Planet x PJ Katz | Dog Days" />
                </div>
              </div>
              <p>Joe Lambert</p>
            </div>
          </div>
          <div class="listen" :class="{show : showListen}">
            <div class="cover">
              <img src="@/assets/images/icons/cover.png" alt="Young Planet x PJ Katz | Dog Days" />
            </div>
            <div class="listen__song">
              <div class="listen__header">
                <h1>Music Player</h1>
              </div>
              <div class="controls one" :class="{show: playToggleOne}">
                <div class="icon" @click="backOne">
                  <img src="@/assets/images/music-player/back.png" alt="filler" />
                </div>
                <div @click="playOne" class="icon play" :class="{active : isPlaying }">
                  <img src="@/assets/images/music-player/play.png" alt="filler" />
                </div>
                <div class="icon pause" :class="{active : isPlaying}" @click="pauseBtn">
                  <img src="@/assets/images/music-player/pause.png" alt="filler" />
                </div>
                <div class="icon" @click="forwardOne">
                  <img src="@/assets/images/music-player/forward.png" alt="filler" />
                </div>
              </div>
              <div class="controls two" :class="{show: playToggleTwo}">
                <div class="icon" @click="backTwo">
                  <img src="@/assets/images/music-player/back.png" alt="filler" />
                </div>
                <div @click="playTwo" class="icon play" :class="{active : isPlaying }">
                  <img src="@/assets/images/music-player/play.png" alt="filler" />
                </div>
                <div class="icon pause" :class="{active : isPlaying}" @click="pauseBtn">
                  <img src="@/assets/images/music-player/pause.png" alt="filler" />
                </div>
                <div class="icon" @click="forwardTwo">
                  <img src="@/assets/images/music-player/forward.png" alt="filler" />
                </div>
              </div>
              <div class="controls three" :class="{show: playToggleThree}">
                <div @click="backThree" class="icon">
                  <img src="@/assets/images/music-player/back.png" alt="filler" />
                </div>
                <div @click="playThree" class="icon play" :class="{active : isPlaying }">
                  <img src="@/assets/images/music-player/play.png" alt="filler" />
                </div>
                <div class="icon pause" :class="{active : isPlaying}" @click="pauseBtn">
                  <img src="@/assets/images/music-player/pause.png" alt="filler" />
                </div>
                <div class="icon" @click="forwardThree">
                  <img src="@/assets/images/music-player/forward.png" alt="filler" />
                </div>
              </div>
              <div class="song-title">
                <h3 @click="edgeToggle">1. Edge Of The World</h3>
              </div>
              <div class="song-title">
                <h3 @click="dazeToggle">2. In A Daze</h3>
              </div>
              <div class="song-title">
                <h3 @click="dogToggle">3. Dog Days</h3>
              </div>
            </div>
          </div>
          <div class="download" :class="{show : showDownload}">
            <div class="download__platform">
              <div class="image">
                <img src="@/assets/images/icons/apple.png" />
              </div>
              <div class="image">
                <img src="@/assets/images/icons/spotify.png" />
              </div>
              <div class="image">
                <img src="@/assets/images/icons/soundcloud.png" />
              </div>
              <div class="image">
                <img src="@/assets/images/icons/tidal.png" />
              </div>
            </div>
          </div>
          <div class="contact" :class="{show : showContact}">
            <div class="contact__platform">
              <div class="image">
                <img src="@/assets/images/icons/mail.png" />
              </div>
              <div class="image">
                <img src="@/assets/images/icons/instagram.png" />
              </div>
              <div class="image">
                <img src="@/assets/images/icons/twitter.png" />
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
      showDog: false,
      dogAnimation: false,
      paperAnimation: false,
      dragOff: false,
      showLogo: true,
      edge: new Audio(require('@/assets/audio/edge.mp3')),
      daze: new Audio(require('@/assets/audio/daze.mp3')),
      dog: new Audio(require('@/assets/audio/dog.mp3')),
      isPlaying: false,
      playToggleOne: false,
      playToggleTwo: false,
      playToggleThree: false,
    }
  },
  methods: {
    creditsToggle() {
      this.showCredits = true
      this.showHome = false
      this.showListen = false
      this.showDownload = false
      this.showContact = false
      this.showCidida = true
      this.showJuly = false
      this.showPj = false
      this.showMitch = false
      this.showJoe = false
      this.showDallas = false
      this.dogAnimation = false
      this.paperAnimation = false
      this.dragOff = false
      this.showLogo = false
    },
    listenToggle() {
      console.log(this.song)
      this.showListen = true
      this.showCredits = false
      this.showHome = true
      this.showDownload = false
      this.showContact = false
      this.showEdge = false
      this.showDaze = false
      this.showDog = false
      this.dogAnimation = false
      this.paperAnimation = false
      this.dragOff = false
      this.showLogo = false
    },
    downloadToggle() {
      this.showDownload = true
      this.showListen = false
      this.showCredits = false
      this.showHome = false
      this.showContact = false
      this.dogAnimation = false
      this.paperAnimation = false
      this.dragOff = false
      this.showLogo = false
    },
    contactToggle() {
      this.showContact = true
      this.showDownload = false
      this.showListen = false
      this.showCredits = false
      this.dogAnimation = false
      this.paperAnimation = false
      this.dragOff = false
      this.showHome = false
      this.showLogo = false
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
      this.dogAnimation = false
      this.paperAnimation = false
      this.dragOff = false
      this.edge.play()
      this.daze.pause()
      this.dog.pause()
      this.isPlaying = true
      this.playToggleOne = true
      this.playToggleTwo = false
      this.playToggleThree = false
    },
    dazeToggle() {
      this.showDaze = true
      this.showEdge = false
      this.showDog = false
      this.showHome = false
      this.dogAnimation = false
      this.paperAnimation = false
      this.dragOff = false
      this.edge.pause()
      this.daze.play()
      this.dog.pause()
      this.isPlaying = true
      this.playToggleTwo = true
      this.playToggleOne = false
      this.playToggleThree = false
    },
    dogToggle() {
      this.showDog = true
      this.showEdge = false
      this.showDaze = false
      this.showHome = false
      this.edge.pause()
      this.daze.pause()
      this.dog.play()
      this.isPlaying = true
      this.playToggleThree = true
      this.playToggleOne = false
      this.playToggleTwo = false
      setTimeout(() => {
        this.paperAnimation = true
      }, 1000);
      setTimeout(() => {
        this.dogAnimation = true
      }, 3000);
      setTimeout(() => {
        this.dragOff = true
      }, 4000)
      setTimeout(() => {
        this.dogAnimation = false
        this.paperAnimation = false
      }, 5000)
    },
    pauseBtn() {
      this.isPlaying = false
      this.edge.pause()
      this.daze.pause()
      this.dog.pause()
    },
    playOne() {
      this.edge.play()
      this.isPlaying = true
    },
    playTwo() {
      this.daze.play()
      this.isPlaying = true
    },
    playThree() {
      this.dog.play()
      this.isPlaying = true
    },
    forwardOne() {
      this.daze.play()
      this.dog.pause()
      this.edge.pause()
      this.isPlaying = true
      this.playToggleTwo = true
      this.playToggleOne = false
      this.playToggleThree = false
    },
    forwardTwo() {
      this.dog.play()
      this.daze.pause()
      this.edge.pause()
      this.isPlaying = true
      this.playToggleTwo = false
      this.playToggleOne = false
      this.playToggleThree = true
    },
    forwardThree() {
      this.edge.play()
      this.daze.pause()
      this.dog.pause()
      this.isPlaying = true
      this.playToggleTwo = false
      this.playToggleOne = true
      this.playToggleThree = false
    },
    backOne() {
      this.dog.play()
      this.daze.pause()
      this.edge.pause()
      this.isPlaying = true
      this.playToggleTwo = false
      this.playToggleOne = false
      this.playToggleThree = true
    },
    backTwo() {
      this.edge.play()
      this.daze.pause()
      this.dog.pause()
      this.isPlaying = true
      this.playToggleTwo = false
      this.playToggleOne = true
      this.playToggleThree = false
    },
    backThree() {
      this.daze.play()
      this.dog.pause()
      this.edge.pause()
      this.isPlaying = true
      this.playToggleTwo = true
      this.playToggleOne = false
      this.playToggleThree = false
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../sass/_homepage.scss"
</style>
