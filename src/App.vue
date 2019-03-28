<template>
  <div id="wrapper" class="toggled">
    <div class="row header">
      <div class="col-2">
        <a onclick="menu_toggle()" class="btn" style="cursor: pointer;">
          <div class="menu-icon"></div>
          <div class="menu-icon"></div>
          <div class="menu-icon"></div>
        </a>
      </div>
      <div class="col-10" align="right">
        <div class="dropdown" style="cursor: pointer;">
          <img src="./assets/img/logo2.png" class="avatar" />
          <button class="dropbtn">
            นายวรายุทธ เทกระโทก
            <i class="fa fa-caret-down"></i>
          </button>
          <div class="dropdown-content">
            <a class="dropdown-item" href=""><i class="fas fa-user"></i>Profile</a>
            <a class="dropdown-item" href=""><i class="fas fa-sign-out-alt"></i>Log
              Out
            </a>
          </div>
        </div>
      </div>
    </div>
    <div id="sidebar-wrapper">
      <ul class="sidebar-nav">
        <li class="logo">
          <div align="center">
            <img src="./assets/img/logo2.png" class="img-responsive" style=" padding-top: 10%;" width="170px">
          </div>
        </li>
        <li>
          <div style="padding: 20px 0; text-indent: 0px;" align="center">
            <span class="brand-line-one"></span><br> 
              <span class="brand-line-second"> DAILY LIFE CORPORATION</span><br> 
          </div>
        </li>
        <li>
          <a href="">
            <div>
              <i class="fab fa-typo3" style="font-size:24px"></i>
              <span style="padding:5px; font-size:15px; "> ประเภทผู้ใช้งาน </span>
            </div>
          </a>
        </li>
        <li>
          <a href="">
            <div>
              <i class="fas fa-user" style="font-size:24px"></i>
              <span style="padding:5px; font-size:15px;"> ผู้ใช้งาน </span>
            </div>
          </a>
        </li>
      </ul>
    </div>
    <div id="page-content-wrapper">
      <div id="app">
        <img alt="Vue logo" src="./assets/logo.png">
        <HelloWorld msg="Welcome to Your Vue.js App" />
      </div>
    </div>
    <center>
      <footer>
        <p>&copy; 2019 - DEILY LIFE CORPORATION</p>
      </footer>
    </center>
  </div>

</template>

<script>
  import HelloWorld from './components/HelloWorld.vue'

  export default {
    name: 'app',
    components: {
      HelloWorld
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>