<template>
  <div id="home">
    
      <div class="row">
        <img src="../img/home.jpg" alt="segonaBackground" id="home-img">
        <div class="col-md-6 col-xs-12 col-sm-8 col-sm-offset-2 col-md-offset-3">
          <img src="../img/SE-logo.png" alt="segonaImage" class="segonaImg">
        </div>
      </div>
      <div class="row home-param">
        <div class="col-md-12 text-center">
          <h1>Welcome to SegonTech</h1>
          <h3>
            <i class="fa fa-quote-left home-icon"></i>
            Where technology meets intelligence
            <i class="fa fa-quote-right home-icon"></i>
            </h3>
        </div>
      </div>
      <div class="row">
        <button class="btn btn-get-started"><span>Get Started</span></button>
      </div>
  </div>
</template>

<script>

export default {
  
}
</script>

<style>
#home-img {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateX(-50%) translateY(-50%);
  height: 100%;
  width: 100%;
  margin: 0;
  z-index: -1;
}

#home:before {
    content: "";
  background: rgba(3, 1, 1, 0.4);
  position: absolute;
  bottom: 0;
  top: 0;
  left: 0;
  right: 0;
}

.segonaImg {
  height: 140px;
  width: 140px;
  margin-left: 235px;
  margin-top: 200px;
}

.home-param {
  text-transform: uppercase;
  margin-top: 40px;
  margin-bottom: 20px;
  color: #fff;
}

#home .btn-get-started {
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  margin-bottom: 108px;
  border-radius: 20px;
  background: transparent;
  border: 2px solid #840000;
  color: #fff;
  transition: all 1s ease;
  outline: 0;
}

#home .btn-get-started:hover {
  color: #840000;
  border-color: #fff;
}

#home .btn-get-started span {
  margin-top: 20px;
  margin-bottom: 20px;
  margin-left: 30px;
  margin-right: 30px;
}

#home .home-param .home-icon {
  position: relative;
  top: -10px;
}
/* .home-overlay {
  content: '';
  background-color: rgba(0,0,0,0.9);
  z-index: -1;
  width: 100%;
  height: 100%;
  position: absolute;
  
} */
</style>
