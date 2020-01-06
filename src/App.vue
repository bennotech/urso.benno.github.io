<template>
  <div id="app">
    <benno-navbar></benno-navbar>
    <router-view></router-view>
    <benno-footer></benno-footer>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=News+Cycle:400,700&display=swap');
@import url("https://use.typekit.net/ccs0hzj.css");

#app {
  font-family: Gibson, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  overflow-x: hidden;
}

#landing-top {
  background-color: #f7f7f7;
  font-family: 'Avenir';
  color: #000;
  margin: 115px -15px 30px;
  border-top: 1px solid rgba(0,0,0,.05);
}

#landing-feature-n {
  font-family: 'Avenir';
  color: #000;
  text-align: left;
  padding: 115px 0 50px;
  background-color: #f7f7f7;
}
@media (min-width: 768px) {
  #landing-feature-n {
    padding-bottom: 75px;
  }
}

#landing-sections {
  font-family: 'Avenir';
  background-color: #f7f7f7;
  color: #000;
}

.benno-container
{
    width: 100%;
    margin-right: auto;
    margin-left: auto;
    padding-right: 40px;
    padding-left: 40px;
    max-width: 1000px;
}
@media (min-width: 576px){
  .benno-container {
    margin-left: auto;
  }
}
@media (min-width: 768px) {
  .benno-container {
    padding-right: 40px;
    padding-left: 40px;
  }
}

.benno-container-sm
{
    width: 100%;
    margin-right: auto;
    margin-left: auto;
    padding-right: 40px;
    padding-left: 40px;
    max-width: 800px;
}
@media (min-width: 576px){
}
@media (min-width: 768px) {
  .benno-container-sm {
    padding-right: 40px;
    padding-left: 40px;
  }
}
.benno-container-lg
{
    width: 100%;
    margin-right: auto;
    margin-left: auto;
    padding-right: 40px;
    padding-left: 40px;
    max-width: 1200px;
}
@media (min-width: 576px){
}
@media (min-width: 768px) {
  .benno-container-lg {
    padding-right: 40px;
    padding-left: 40px;
  }
}

.benno-container-xl
{
    width: 100%;
    margin-right: auto;
    margin-left: auto;
    padding-right: 40px;
    padding-left: 40px;
}
@media (min-width: 576px){
}
@media (min-width: 768px) {
  .benno-container-xl {
    padding-right: 40px;
    padding-left: 40px;
    max-width: 1400px;
  }
}

.container-left {
  margin-left: auto;
}
@media (min-width: 576px){
  .container-left {
    margin-left: 45px !important;
  }
}
@media (min-width: 768px) {
  .container-left {
    margin-left: 85px !important;
  }
}
@media (min-width: 992px) {
  .container-left {
    margin-left: 105px !important;
  }
}
@media (min-width: 1200px) {
  .container-left {
    margin-left: 145px !important;
  }
}

.benno-lg-container {
    width: 100%;
    padding-right: 40px;
    padding-left: 40px;
    margin-right: auto;
    margin-left: auto;
}
@media (min-width: 576px) {}
@media (min-width: 768px) {}
@media (min-width: 992px) {
  .benno-lg-container {
    padding-right: 40px;
    padding-left: 40px;
    max-width: 1500px;
  }
}
@media (min-width: 1200px) {}

.benno-xl-container {
    width: 100%;
    padding-right: 40px;
    padding-left: 40px;
    margin-right: auto;
    margin-left: auto;
}
@media (min-width: 576px) {}
@media (min-width: 768px) {}
@media (min-width: 992px) {}
@media (min-width: 1200px) {}

.feature-section {
  padding: 0 0 75px;
}
.feature-section:first-child {
  padding-top: 50px;
}

@media (min-width: 768px) {
  .feature-section {
    padding: 0 0 75px;
  }
  .feature-section:first-child {
    padding-top: 75px;
  }
}

.text-xl {
  font-size: 36px !important;
}
.text-lg {
  font-size: 24px !important;
}
.text-md {
  font-size: 18px !important;
}
.text-sm {
  font-size: 16px !important;
  padding-top: 4px;
}
.text-xs {
  font-size: 14px !important;
  padding-top: 20px;
}
@media (min-width: 480px){
  .text-xl {
    font-size: 48px !important;
  }
  .text-lg {
    font-size: 36px !important;
  }
  .text-md {
    font-size: 24px !important;
  }
  .text-sm {
    font-size: 18px !important;
    padding-top: 8px;
  }
  .text-xs {
    font-size: 16px !important;
  }
}
@media (min-width: 768px) {
  .text-xl {
    font-size: 60px !important;
  }
  .text-lg {
    font-size: 48px !important;
  }
  .text-md {
    font-size: 28px !important;
  }
  .text-sm {
    font-size: 20px !important;
    padding-top: 12px;
  }
  .text-xs {
    font-size: 18px !important;
  }
}
@media (min-width: 992px) {
  .text-xl {
    font-size: 72px !important;
  }
  .text-lg {
    font-size: 60px !important;
  }
  .text-md {
    font-size: 32px !important;
  }
  .text-sm {
    font-size: 24px !important;
    padding-top: 20px;
  }
  .text-xs {
    font-size: 18px !important;
  }
}

.text-heavy {
  font-weight: 600 !important;
}
.text-xl-heavy {
  font-weight: 900 !important;
}

.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}

.text-link {
  padding-top: 40px !important;
}
.text-link a {
  color: #000;
  line-height: 1.6;
  display: block;
  width: fit-content;
  border-bottom: 3px solid #000;
}
.text-link a:hover {
  cursor: pointer;
  color: #000;
  text-decoration: none;
}
.text-link a::after {
  font-family: "Font Awesome 5 Free";
  font-weight: 900;
  content: "\f061";
  color: #000;
  margin-left: 8px;
  display: inline-block;
  font-size: 16px;
}
.text-link a:hover::after {
  color: #000;
}

.inline-link {
}
.inline-link a {
  display: inline-block;
  color: #000;
  line-height: 1.6;
  width: fit-content;
  border-bottom: 3px solid #000;
}
.inline-link a:hover {
  cursor: pointer;
  color: #000;
  text-decoration: none;
}
.inline-link a::after {
  font-family: "Font Awesome 5 Free";
  font-weight: 900;
  content: "\f061";
  color: #000;
  margin-left: 8px;
  display: inline-block;
  font-size: 16px;
}
.inline-link a:hover::after {
  color: #000;
}

.record-items {
  font-family: 'Avenir';
  color: #000;
  border: 3px solid #000;
  padding: 40px;
  margin-top: 5px;
  margin-bottom: 50px;
  display: block;
  position: relative;
  min-height: calc(100% - 55px);
}

.record-items:hover {
  color: #000;
  cursor: pointer;
  text-decoration: none;
}

.icon-link::after {
  font-family: "Font Awesome 5 Free";
  font-weight: 900;
  content: "\f061";
  color: #000;
  margin-left: 8px;
  display: inline-block;
  font-size: 24px;
  transform: rotate(0deg);
  transition: 1s;
}

.record-items:hover .icon-link::after {
  transform: rotate(450deg);
  transition: 1s;
}

.record-text-top-cat {
  font-family: brandon-grotesque, sans-serif;
  font-size: 16px;
  font-weight: 600;
  padding: 0 5px;
  text-transform: uppercase;
  position: absolute;
  top: -53px;
  left: -15px;
  background-color: #f7f7f7;
  z-index: 2;
}

.record-text-top-cat::after {
  content: "";
  background: repeating-linear-gradient(60deg, #000, #000 1px, #fff 1px, #fff 1.25px);
  width: 0;
  position: absolute;
  bottom: 0;
  left: 0;
  height: 11px;
  z-index: -1;
}

.record-text-top-cat.active::after {
  width: 100%;
}
.record-items:hover .record-text-top-cat::after {
  width: 100%;
}
.featured-items {
  font-family: 'Avenir';
  color: #000;
  width: 100%;
  margin: 0 0 75px auto;
  padding-top: 75px;
}

.featured-items::before {
  content: "";
  background: repeating-linear-gradient(60deg, #000, #000 1px, #fff 1px, #fff 1.25px);
  background-color: #f7f7f7;
  height: 24px !important;
  margin: 0px 0px 0 0 !important;
  width: 0;
  position: absolute;
  left: 15px;
  top: 85px;
}
@media (min-width: 992px) {
  .featured-items {
    width: calc(100% - 500px); margin-right: auto !important;
  }
  .featured-items:first-child::before {
    width: 200px;
  }
}

.crazy-border {
  height: 50px;
  margin: 0 0 75px;
  background: repeating-linear-gradient(60deg, #000, #000 1px, #fff 1px, #fff 1.25px);
  background-color: #f7f7f7;
}

</style>
