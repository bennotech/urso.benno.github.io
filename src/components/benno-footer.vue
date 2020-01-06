<template>
  <div>
    <div id="footer">
      <div class="container">
        <div class="row align-items-top">
          <div class="col-6 text-left">
            <div class="copyright">
            © 2019 Urso Security
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  name: 'benno-footer',
  computed: {
  },
  data () {
    return {
      showfooter: true,
      scrollPosition: null
    }
  },
  methods: {
    updateScroll () {
      this.scrollPosition = window.scrollY
    }
  },
  mounted () {
    window.addEventListener('scroll', this.updateScroll)
  },
  beforeDestroy () {
    window.removeEventListener('scroll', this.updateScroll)
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#footer {
  width: 100%;
  background-color: #223f58;
  z-index: 99;
  padding: 150px 30px 400px;
}
.icon-box {
  height: 50px;
}
.copyright {
  color: #fff;
  padding-top: 10px;
  font-size: 12px;
}
</style>
