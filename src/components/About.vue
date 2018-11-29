<template>
  <div id="about">
    <div class="row">
      <img src="../img/about.jpg" alt="aboutImage" class="about-bg-img">
      <div class="col-md-12 few-words">
        <div class="text-center">
          <h1>Few Words About Us</h1>
        <p>SegonaTech is a Nepal based software solution company that focuses on delivering high quality, timely, and cost-effective software development.Our solutions are based on innovative methodologies to ensure optimization on Return On Investments (ROI) to our customers. </p>

        <p>At SegonaTech, we help companies transform ideas into successful products.</p>
        </div>
        <div class="col-md-12 fewer-words text-justify">
        <div class="col-md-4 fewer-words-item">
          <div class="col-md-4">
            <div>
              <i class="fa fa-building fa-3x about-icon"></i>
            </div>
          </div>
          <div class="col-md-8">
            <h3>Company</h3>
            <p>We help clients to move their services and products up the value chain and create a unique experience for their customers.</p>
          </div>
        </div>
        <div class="col-md-4 fewer-words-item">
          <div class="col-md-4">
            <div>
              <i class="fa fa-eye fa-3x about-icon"></i>
            </div>
          </div>
          <div class="col-md-8">
            <h3>Why Segonatech?</h3>
            <p>We believe that ‘change is the only consistent’. Our innovation helps clients find real solutions to real problems.</p>
          </div>
        </div>
        <div class="col-md-4 fewer-words-item">
          <div class="col-md-4">
            <div>
              <i class="fa fa-bar-chart fa-3x about-icon"></i>
            </div>
          </div>
          <div class="col-md-8">
            <h3>Company</h3>
            <p>To deliver cost effective value propositions to our customers through our expertise in IT, Design and Outsourcing solutions.</p>
          </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
}
</script>

<style>

#about .about-bg-img {
  position: relative;
  top: 50%;
  height: 662px;
  width: 100%;
  z-index: -2;
}

#about:before {
  content: "";
  background: rgba(0,0,0,0.6);
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: -1;
}

#about .few-words {
  position: absolute;
  margin-top: 150px;;
  top: -1px;
  color: #fff;
}

#about .fewer-words {
  margin-top: 65px;
}

#about .fewer-words .about-icon {
  margin-left: 50px;
  margin-top: 10px;
  border: 2px solid #840000;
  border-radius: 50%;
  padding: 15px;
  align-content: center;
}

#about .fewer-words:before {
  content: '';
  background: rgba(0,0,0,0.6);
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}

#about .fewer-words .fewer-words-item {
  margin: 30px 0;
  cursor: default;
}

#about .fewer-words .fewer-words-item .about-icon {
  transition: all 2s ease;
}

#about .fewer-words .fewer-words-item:hover .about-icon {
  transform: translateX(-40px);
  color: #840000;
  border-color: #fff;
}
</style>
