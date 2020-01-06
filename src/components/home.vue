<template>
  <div>

    <div class="container-fluid" style="margin-bottom: 500px;">
      <div class="row">
        <div class="col-12 text-center mx-auto position-relative">
          <div class="landing-box text-center mx-auto">
            <h1>
              Urso Security. Make a difference.
            </h1>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>

export default {
  name: 'home',
  computed: {
  },
  methods: {
  },
  data () {
    return {
    }
  },
  mounted () {
  }
}
</script>

<style scoped>
#grate-home {
  color: #fff;
  background-color: #0e3f65;
  border-bottom: 1px solid rgba(30, 91, 86, .1);
}

.left-image {
  min-height: unset;
  max-height: 50vh;
  height: 100%;
  width: calc(100% + 30px);
  margin-left: -15px;
  object-fit: cover;
}
@media (min-width: 768px) {}
@media (min-width: 992px) {
  .left-image {
    min-height: calc(100vh - 50px);
    max-height: unset;
  }
}
.left-overlay {
  background-image: linear-gradient(158deg,rgba(0,0,0,.3) 15%,rgba(0,0,0,0) 30% 100%);
  position: absolute;
  top: 0;
  left: 0;
  width: calc(100%);
  height: 100%;
}
.left-logo {
  position: absolute;
  top: 30px;
  left: 30px;
  height: 30px;
}
@media (min-width: 992px) {
  .left-logo {
    height: 50px;
  }
}
.top-links {
  max-width: 600px;
  margin: 50px auto;
  text-align: right;
}
.top-links a {
  font-weight: 600;
  font-size: 18px;
  margin-left: 20px;
  color: #0084e1;
  text-decoration: none;
  cursor: pointer;
}
.top-links a:hover {
  color: #223f58;
}
.landing-box {
  max-width: 600px;
  margin: 50px auto auto;
}
@media (min-width: 992px) {
  .landing-box {
    margin: 300px auto auto;
  }
}
.grate-search {
  border-radius: 2px;
  border: 1px solid rgba(0,0,0,.5);
  padding: 6px 20px;
  font-size: 18px;
  cursor: text;
  width: calc(100% - 150px - 20px);
}
.search-btn {
  display: inline-block;
  color: #fff;
  background-color: #0084e1;
  padding: 6px 0;
  width: 150px;
  text-align: center;
  font-size: 18px;
  border: 1px solid #0084e1;
  border-radius: 2px;
  margin-left: 20px;
  cursor: pointer;
}

#grate-body {
  color: #000;
  background-color: #fff;
  padding: 100px 0 0;
}
#grate-about {
  color: #000;
  background-color: rgba(0,0,0,.1);
  padding: 0;
}
.section {
  padding: 100px 0;
}
.section.sm {
  padding: 50px 0;
}

h1 {
  font-family: Gibson, sans-serif;
  font-size: 44px;
  line-height: 1.2;
  font-weight: 600;
  margin: 25px 0;
  width: 100%;
  color: #000;
}

h1 span {
  color: #ced4da;
}

h2 {
  font-family: Gibson, sans-serif;
  font-size: 32px;
  line-height: 1.25;
  font-weight: 500;
  padding-bottom: 12px;
  margin-bottom: 0;
  color: #000;
  max-width: 500px;
}

h2 span {
  color: #ced4da;
}
h3 {
  font-family: Gibson, sans-serif;
  font-size: 18px;
  line-height: 28px;
  font-weight: 600;
  padding-bottom: 12px;
  margin-bottom: 0;
  color: #000;
}
h4 {}
h5 {
  font-family: Gibson, sans-serif;
  text-align: center;
  margin: auto;
  font-size: 22px;
  line-height: 32px;
  padding-bottom: 44px;
  width: 100%;
  color: #313131;
  font-weight: 400;
}
h6 {
  font-family: Gibson, sans-serif;
  font-size: 18px;
  font-weight: 300;
  line-height: 1.25;
  letter-spacing: .5px;
  color: #000;
}
p {
  font-family: Gibson, sans-serif;
  font-size: 16px;
  line-height: 24px;
  color: #000;
  font-weight: 300;
}

.title-block {
  max-width: 1000px;
  margin: auto;
}

.signup-block {
  text-align: center;
  max-width: 550px;
  margin: auto;
}
.signup-block p {
  max-width: 100%;
}

.card-icon {
width: 48px;
height: 48px;
margin: 100px auto 24px;
}

.card-icon.sm {
  width: 32px;
  height: 32px;
  margin: 50px auto 24px;
}

.grate-btn {
  font-family: Gibson, sans-serif;
  padding: 22px 48px 20px;
  font-size: 14px;
  font-weight: 500;
  line-height: 1;
  cursor: pointer;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #0e3f65;
  background: rgb(255, 255, 255);
  padding: 22px 48px 20px;
  border-radius: 5px;
  border-width: 1px;
  border-style: solid;
  border-color: #0e3f65;
  -o-border-image: initial;
  border-image: initial;
  margin: 20px;
}
.grate-btn:hover {
  background-color: #fff;
  color: #0e3f65;
  text-decoration: underline;
  cursor: pointer;
}
.grate-btn.solid {
  background-color: #0e3f65;
  border-color: #0e3f65;
  color: #fff;
}
.grate-btn.solid:hover {
  text-decoration: underline;
  cursor: pointer;
}

.gratetext-sm {
  font-size: 13px;
  font-weight: 600;
}

.text-white {
  color: #fff !important;
}

.icon-box {
  width: 100px;
  margin: -10px 5px 0;
}

.text-heavy {
  font-weight: 600;
}

.status-circle {
  margin: 50px auto;
  width: 125px;
  height: 125px;
  border-radius: 50%;
  border: 6px solid #0e3f65;
  text-align: center;
  padding: 30px 0;
}
.status-circle span {
  text-align: center;
  font-size: 36px;
  color: #0e3f65;
}

.pricing {
  position: relative;
  padding: 7px 0 0 75px;
  margin: 0 0 50px;
}
.pricing::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  border-radius: 50%;
  width: 40px;
  height: 40px;
  border: 4px solid #0e3f65;
}
</style>
