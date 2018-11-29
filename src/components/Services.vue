<template>
    <div id="services">
        <div class="row">
            <img src="../img/services.jpg" alt="servicesImage" class="service-bg-img">
            <div class="col-md-12 services-words">
                <div class="text-center services-title-words">
                    <h1>Services</h1>
                    <p>SegonaTech is grounded firmly on the foundations of trust, teamwork and dedication.</p>
                </div>
                <div class="row services-body text-justify">
                    <div class="col-md-4">
                        <div class="box">
                            <i class="fa fa-window-maximize fa-3x about-icon"></i>
                            <div class="box-inside">
                                
                                <h3>Application Development</h3>
                                <p>We develop high quality business applications that help you increase operational efficiency and sustain your competitive advantage.</p>
                            </div>
                            
                        </div>
                </div>
                <div class="col-md-4">
                    <div class="box">
                        <i class="fa fa-window-restore fa-3x about-icon"></i>
                        <div class="box-inside">
                            <h3>Web Development</h3>
                        <p>Our proficient team develops custom solution for companies across diverse industry verticals, irrespective of the size and budget.</p>
                        </div>
                        
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="box">
                        <i class="fa fa-mobile fa-3x about-icon"></i>
                        <div class="box-inside">
                            <h3>Mobile Development</h3>
                        <p>We offer diverse mobility solutions keeping your long-term business requirements in reach and fulfill your Android and IOS development.</p>
                        </div>
                        
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="box">
                        <i class="fa fa-file fa-3x about-icon"></i>
                        <div class="box-inside">
                            <h3>Application Maintenance</h3>
                        <p>SegonaTech assists you in customized application development as well as ongoing maintenance.</p>
                        </div>
                        
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="box">
                        <i class="fa fa-bug fa-3x about-icon"></i>
                        <div class="box-inside">
                            <h3>Application Testing</h3>
                        <p>SegonaTech ensures that the products built and serviced are at high quality by emphasizing on ‘Software Quality’ based on well-defined models.</p>
                        </div>
                        
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="box">
                        <i class="fa fa-paint-brush fa-3x about-icon"></i>
                        <div class="box-inside">
                            <h3>Graphic Designing</h3>
                        <p>SegonaTech design logo for business industry for providing identity.</p>
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
    
}
</script>

<style>

#services .service-bg-img {
    position: relative;
    width: 100%;
    height: 662px;
    z-index: -2;
}

#services:before {
    content: '';
    position: absolute;
    background: rgba(0,0,0,0.9);
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: -1;
}

#services .services-words {
    position: absolute;
    top:0px;
    color: #fff;
}

#services .services-words .services-title-words {
    margin-top: 90px;
}

#services .services-body .box {
    border: 2px solid #840000;
    margin-top: 40px;
    margin-bottom: 20px;
    padding: 20px;
    border-radius: 20px;
    height: 180px;
    transition: all 2s ease;
}

#services .services-body .box:hover {
    border-color: #fff;
    color: #840000;
}

#services .services-body .box:hover .about-icon {
    color: #840000;
    background: #fff;
    border-color: #840000;
}

#services .services-body .box .about-icon {
    position: relative;
    left: 50%;
    transform: translateX(-50%);
    top: -60px;
    border: 2px solid #fff;
    border-radius: 50%;
    padding: 20px;
    transition: all 2s ease;
    background: #840000;
    cursor: default;
}

#services .services-body .box .box-inside {
    position: relative;
    top: -70px;
    cursor: default;
}
</style>
