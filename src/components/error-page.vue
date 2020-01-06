<template>
<div>
  <div id="benno-body">
    <div class="benno-container">
      <div class="benno-textbox">
        <div class="row">
          <div class="col-12 text-left">
            <h1>Error 404, page not found. Your best bet?</h1>
            <h1>Head back to
              <router-link to="/" class="return-link">
                grate.co</router-link>.</h1>
          </div>
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
  }
}
</script>

<style scoped>

#benno-body {
  font-family: Gibson, sans-serif;
  color: #000;
  padding: 200px 0;
  font-weight: 400;
  letter-spacing: .85px;
  position: relative;
  min-height: calc(100vh - 200px);
}

.benno-textbox {
  max-width: 600px;
  padding-right: 50px;
}
.benno-textbox h1 {
  font-size: 24px;
  color: #6e6f73;
  margin-bottom: 5px;
  font-weight: 400;
}
.return-link {
  color: #0e3f65;
}
.return-link:hover {
  color: #0e3f65;
  cursor: pointer;
  text-decoration: none;
}
.benno-textbox p {
  font-size: 18px;
  color: #757575;
  line-height: 1.35;
}
.benno-textbox h2 {
  font-size: 18px;
  color: #c3c3c3;
  line-height: 1.35;
  margin-top: 40px;
}
.red {
  color: #ed1c24 !important;
}
.red:hover {
  border-color: #ca1a21 !important;
  color: #ca1a21 !important;
}
.blue {
  border-color: #0e3f65 !important;
  color: #0e3f65 !important;
}
.blue:hover {
  color: #757575 !important;
  border-color: #757575 !important;
  text-decoration: none;
}
.link-btn {
  padding-left: 5px;
}
.link-btn:hover {
  cursor: pointer;
}

.spec {
  font-family: brandon-grotesque, sans-serif;
  width: 206px;
  height: calc(100% - 10px);
  margin: 5px 0;
  letter-spacing: .85px;
  font-size: 14px;
  font-weight: 600;
  color: #000;
  display: inline-block;
  border: 2px solid #000;
  padding: 10px 0;
}

.spec.dark {
  color: #fff;
  background-color: #000;
}

.sample-text {
  font-size: 13px;
  font-weight: 600;
  color: #000;
  text-align: left;
  padding: 8px 20px;
  margin-bottom: 20px;
  border-top: 1px solid rgba(0,0,0,.1);
  border-bottom: 2px solid rgba(0,0,0,1);
}
.sample-search {
font-size: 20px;
font-weight: 600;
color: #000;
text-align: left;
padding: 16px 20px;
margin-bottom: 20px;
max-width: 600px;
margin: 0 auto;
border: 1px solid #000;
border-radius: 40px;
}

.searchbar-box {
  border-radius: 3px;
  font-size: 20px;
  padding: 6px 0;
  background-color: #fff;
}
.searchbar-icon {
  margin-right: 10px;
  color: #000;
}
.searchbar-input {
  width: calc(100% - 30px);
  border: none;
  font-weight: 600;
  color: #000;
  background-color: #fff;
}
.searchbar-input::placeholder {
  font-weight: 400;
  color: #000;
}
.searchbar-input:focus {
  outline: none;
}
.text-link a {
  border-color: #2a7ab2 !important;
}
.text-link a:hover {
  color: #2a7ab2 !important;
}

.text-link a:hover::after {
  color: #2a7ab2 !important;
}

.inline-link a {
  border-color: #2a7ab2 !important;
}
.inline-link a:hover {
  color: #2a7ab2 !important;
}
.inline-link a:hover::after {
  color: #2a7ab2 !important;
}

.record-text-top-cat::after {
  background: repeating-linear-gradient(60deg, #2a7ab2, #2a7ab2 1px, #fff 1px, #fff 1.25px) !important;
}

.featured-items::before {
  background: repeating-linear-gradient(60deg, #2a7ab2, #2a7ab2 1px, #fff 1px, #fff 1.25px);
  top: 0;
}

.crazy-border {
  background: repeating-linear-gradient(60deg, #2a7ab2, #2a7ab2 1px, #fff 1px, #fff 1.25px) !important;
}

.record-items:hover .icon-link::after {
  color: #2a7ab2;
}

@media (min-width: 992px) {
  .featured-items {
    width: calc(100% - 250px) !important;
    margin-left: 250px !important;
  }
}
@media (min-width: 1200px) {
  .featured-items {
    width: calc(100% - 500px) !important;
    margin-left: 250px !important;
  }
}

</style>
