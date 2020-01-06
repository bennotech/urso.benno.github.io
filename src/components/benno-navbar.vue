<template>
  <div>

    <div id="navbar">
      <div class="container-fluid">
        <div class="row align-items-center">
          <div class="col-12 text-center">
            <div class="grate-navlinks">
              <router-link to="/" class="link">
                URSO SECURITY
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="spacer">
    </div>

  </div>
</template>

<script>

export default {
  name: 'benno-navbarnew',
  computed: {
  },
  data () {
    return {
    }
  },
  methods: {
  },
  mounted () {
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#navbar {
  position: relative;
  width: 100%;
  background-color: #223f58;
  color: #fff;
  z-index: 99;
  border-bottom: 1px solid #223f58;
  height: 70px;
}

.grate-navlinks {
  display: inline-block;
  width: fit-content;
  height: 70px;
}

.grate-navlinks .link {
  color: inherit;
  display: inline-block;
  font-weight: 300;
  cursor: pointer;
  font-size: 16px;
  white-space: nowrap;
  letter-spacing: .5px;
  height: 16px;
  line-height: 1;
  margin: 27px 0;
}

.grate-navlinks .link:hover {
  text-decoration: underline;
  cursor: pointer;
}

</style>
