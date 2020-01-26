<template>
  <div>
    <div id="front-page-wrapper">
      <NavBar></NavBar>
      <logo class="logo" />
      <div id="textblock">
        <h3 class="bold" style="margin-bottom: 10px;">比邻主义标准申请套装</h3>
            <p class="gray">全面测评  |  冷静规划  |  客观选校  |  严选背景提升  |  文书训练营<br />
        开脑洞肝文书  |  美文润色  |  透明提交  |  全面跟进  |  境外福利</p>
      </div>
      <div id="contact">
        <div style="margin-right: 5%;">
          <p>
          中国： +86-400-022-7623 <br>
          美国： +1-(202)-768-8923
          </p> 
        </div>
        <div style="margin-right: 5%;">
          <p>
          周一至周五 <br>
          9:00 to 24:00
          </p>
        </div>
        <div><p>info@blinism.com</p></div>
        <p><img id="qrcode" style="position:absolute;" src="./assets/qrcode.jpg" alt="qrcode"></p>
        
      </div>
    </div>
    
    <div style="background-color: #f4f7fa;">
      <Subtitle />
      <Step1 />
      <Step2 />
      <Step3 />
      <Step4 />
      <Step5 />
      <Step6 />
      <img src="./assets/banner.svg" alt="bot_banner" style="width: 100%;">
    </div>
    <img src="./assets/footer.svg" alt="footer" style="width: 100%;">

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue'
import logo from './components/logo.vue'
import Subtitle from './components/Subtitle.vue'
import Step1 from './components/Step1.vue'
import Step2 from './components/Step2.vue'
import Step3 from './components/Step3.vue'
import Step4 from './components/Step4.vue'
import Step5 from './components/Step5.vue'
import Step6 from './components/Step6.vue'



export default {
  name: 'app',
  components: {
    NavBar,
    logo,
    Subtitle,
    Step1,
    Step2,
    Step3,
    Step4,
    Step5,
    Step6
  }
}
</script>

<style>
h3, h2, h1, p {
  margin: 0;
}
@media only screen and (min-width: 1400px) {
  p {
    font-size: 1.3em;
  }
  h3 {
    font-size:1.4em;
  }
  h2 {
    font-size: 1.5em;
  }
  #qrcode {
    bottom: 10% !important;
  }
}
#logo {
  height: 60vh;
}
#contact {
  height: 70px;
    width: 70%;
    /* position: relative; */
    float: right;
    background-color: #E678AF;
    padding: 10px;
    padding-left: 20px;
    box-sizing: border-box;
    border-radius: 5px;
    color: white;
    display: flex;
    flex: wrap;
}

#front-page-wrapper {
  height: 100vh;
  width: 100%;
}
#textblock {
    margin: 10px auto;
    text-align: center;
    margin-bottom: 3%;
}
#qrcode {
    position: absolute;
    bottom: 50px;
    height: 14%;
    right: 15%;
}
.bold {
  font-weight: bold;
}
.gray {
  color: gray;
}
body {
  margin: 0px;
}
.steps {
  position: relative;
    left: 50%;
    width: 80%;
    margin-left: -40%;
    margin-top:5%;
}

</style>
