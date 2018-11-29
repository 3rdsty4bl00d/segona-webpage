<template>
    <div id="facts">
        <div class="row">
            <img src="../img/facts.jpg" alt="facts-image" class="facts-bg-img">
            <div class="col-md-12 facts-words">
                <div class="text-center">
                    <h1>Facts</h1>
                    <p>Our philosophy is to keep our customers happy. We exceed customer expectation and achieve customer delight.</p>
                </div>
                <div class="row facts-numbers text-center">
                    <div class="col-md-3 facts-highlight">
                        <div>
                            <i class="fa fa-fire fa-3x about-icon"></i>
                        </div>
                        <div class="counter">150</div>
                        <div class="facts-title">
                            <h3>Clients</h3>
                        </div>
                    </div>
                    <div class="col-md-3 facts-highlight">
                        <div>
                            <i class="fa fa-codepen fa-3x about-icon"></i>
                        </div>
                        <div class="counter">50</div>
                        <div class="facts-title">
                            <h3>Project</h3>
                        </div>
                    </div>
                    <div class="col-md-3 facts-highlight">
                        <div>
                            <i class="fa fa-trophy fa-3x about-icon"></i>
                        </div>
                        <div class="counter">500</div>
                        <div class="facts-title">
                            <h3>Hours of Support</h3>
                        </div>
                    </div>
                    <div class="col-md-3 facts-highlight">
                        <div>
                            <i class="fa fa-users fa-3x about-icon"></i>
                        </div>
                        <div class="counter">29</div>
                        <div class="facts-title">
                            <h3>Hard Workers</h3>
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

#facts .facts-bg-img {
    position: relative;
    width: 100%;
    height: 662px;
    z-index: -2;
}

#facts:before {
    content: '';
    background: rgba(0,0,0,0.6);
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: -1;
}

#facts .facts-words {
    position: absolute;
    top: -1px;
    margin-top: 150px;
    color: #fff;
}

#facts .facts-words .facts-numbers {
    margin-top: 80px;
    margin-left: 10px;
    margin-right: 10px;
    padding: 40px 0;
}

#facts .facts-words .facts-numbers .facts-highlight:before {
    content: '';
    background: rgba(0,0,0,0.6);
    position: absolute;
    top: 0;
    bottom: 0;
    left: 8px;
    right: 8px;
    border-radius: 20px;
}

#facts .facts-words .facts-numbers .facts-highlight .counter {
    font-size: 30px;
}

#facts .facts-words .facts-numbers .facts-highlight .about-icon {
    position: relative;
    margin-top: 40px;
    transition: all 1.5s ease;
    cursor: default;
}

#facts .facts-words .facts-numbers .facts-highlight .facts-title {
    position: relative;
    margin-top: 20px;
    margin-bottom: 40px;
    transition: all 2s ease;
    cursor: default;
}

#facts .facts-words .facts-numbers .facts-highlight .counter {
    position: relative;
    margin-top: 40px;
    transition: all 2s ease;
    cursor: default;
}

#facts .facts-words .facts-numbers .facts-highlight:hover .about-icon {
    transform: translateY(-20px);
    color: #840000;
}

#facts .facts-words .facts-numbers .facts-highlight:hover .facts-title {
    color: #840000;
}

#facts .facts-words .facts-numbers .facts-highlight:hover .counter {
    color: #840000;
}
</style>
