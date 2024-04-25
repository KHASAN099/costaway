<template>
  <div class="container contdop">
    <div class="main-1">
        <p class="main-1-text">Latest episodes</p>
        <a href="" class="main-1-link">View all episodes</a>
    </div>
    <div class="main-2">
        <div class="main-2-main">
            <img src="../assets/img/main-2.png" alt="">
            <div class="main-2-list">
                <p class="Gear">Gear</p>
                <p class="Episode3">Episode 3</p>
                <p class="main-2-list-text">Should you get outboard audio gear?</p>
                <p class="main-2-list-text1">Is hardware really worth it when it comes to podcasting? The answer is...it depends. Here’s our reasons on why you might want to consider picking something up.</p>
                <a href=""><p class="view">View Episode Details</p></a>
            </div>
        </div>
        <div class="main-2-main">
            <img src="../assets/img/main-3.png" alt="">
            <div class="main-2-list">
                <p class="Gear tips">Tips & Tricks</p>
                <p class="Episode3">Episode 2</p>
                <p class="dop main-2-list-text">Mic tricks to take you to the next level</p>
                <p class=" main-2-list-text1 ">Stop rolling with those default settings on your mic. These small tweaks will take you from sounding good to great.</p>
                <a href=""><p class="view">View Episode Details</p></a>
            </div>
        </div>
        <div class="main-2-main">
            <img src="../assets/img/main-4.png" alt="">
            <div class="main-2-list">
                <p class="Gear">Gear</p>
                <p class="Episode3">Episode 1</p>
                <p class="main-2-list-text">The best microphone under $200</p>
                <p class="main-2-list-text1">With so many microphones on the market, how are you supposed to know what’s the best? Take a look at our top picks.</p>
                <a href=""><p class="view">View Episode Details</p></a>
            </div>
        </div>
    </div>
    <div class="main-3">
        <div class="main-3-block">
            <P class="main-3-text1">Meet your host</P>
            <p class="main-3-text2">Jacob Paulaner</p>
            <p class="main-3-text3">Jacob has a background in audio engineering, and has been podcasting since the early days.</p>
            <p class="main-3-text4">He’s here to help you level up your game by sharing everything he’s learned along the way.</p>
        </div>
        <img src="../assets/img/main-5.png" alt="">
    </div>
    <div class="main-4">
        <div class="main-4-main">
            <div class="main-4-text">
                <p class="main-4-text1">Email Newsletter</p>
                <p class="main-4-text2">Subscribe for updates</p>
            </div>
            <div class="main-4-feedback">
                <input type="text" placeholder="Name" class="main-4-input1">
                <input type="text" placeholder="Email" class="main-4-input1">
                <button class="main-4-btn">Submit</button>
            </div>
        </div>
    </div>
    <div class="main-5">
        <div class="main-5-main">
            <i class="far fa-star"></i>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.contdop{
    padding: 93px 70px 0 70px; 
}
.main-1{
    display: flex;
    justify-content: space-between;
    margin-bottom: 40px;
}
.main-1-text{
color: #FFF;
font-size: 64px;
line-height: 79.2px;
letter-spacing: 2.88px;
}
.main-1-link{
width: 178px;
height: 51px;
border-radius: 6px;
background: #118DA8;
display: flex;
align-items: center;
justify-content: center;
color: #FFF;
font-size: 17px;
line-height: 27px;
margin-top: 22px;
}
.main-2{
    margin-bottom: 260px;
    display: grid;
    gap: 60px;
}
.main-2-main{
border-radius: 32px;
background: #000;
display: flex;
padding: 40px;
}
.main-2-list{
    margin-left:53px
}
.Gear{
width: 73px;
height: 27px;
border-radius: 6px;
background: #191919;
color: #FFF;
font-size: 18px;
line-height: 27px;
text-align: center;
margin-bottom: 40px;
}
.Episode3{
color: #118DA8;
font-size: 17px;
line-height: 27px;
margin-bottom: 18px;
}
.main-2-list-text{
width: 701px;
color: #FFF;
font-size: 64px;
line-height: 70.4px;
letter-spacing: 2.56px;
margin-bottom: 28px;
}
.main-2-list-text1{
width: 757px;
color: rgba(255, 255, 255, 0.70);
font-size: 22px;
line-height: 33px;
margin-bottom: 30px;
}
.view{
width: 208px;
height: 51px;
border-radius: 6px;
background: #118DA8;
color: #FFF;
font-size: 18px;
line-height: 27px;
display: flex;
justify-content: center;
align-items: center;
}

.dop{
    width: 676px;
}
.tips{
width: 136px;
height: 27px;
}
.main-3{
display: flex;
justify-content: space-between;
align-items: center;
margin-bottom: 200px;
}
.main-3-block-circ{
width: 112px;
height: 112px;
border-radius: 400px;
background: #118DA8;
margin-bottom: 20px;
display: flex;
align-items: center;
justify-content: center;

}
.main-3-block-img{
width: 60px;
height: 71px;
}
.main-3-text1{
color: #118DA8;
font-size: 18px;
line-height: 27px;
}
.main-3-text2{
color: #FFF;
font-size: 65px;
line-height: 79.2px;
letter-spacing: 2.88px;
margin-bottom: 28px;
}
.main-3-text3{
color: rgba(255, 255, 255, 0.70);
font-size: 22px;
line-height: 33px;
margin-bottom: 33px;
}
.main-3-text4{
color: rgba(255, 255, 255, 0.70);
font-size: 22px;
line-height: 33px;
}
.main-4{
border-radius: 32px;
background: #000;
height: 387px;
}
.main-4-main{
    padding:60px;
    display: flex;
    justify-content: space-between;
}
.main-4-text1{
color: #118DA8;
font-size: 18px;
line-height: 27px;
margin-bottom: 26px;
}
.main-4-text2{
color: #FFF;
font-size: 72px;
line-height: 79.2px;
letter-spacing: 2.88px;
width: 431px;
}
.main-4-feedback{
    display: flex;
    flex-direction: column;
    gap: 20px
}
.main-4-input1{
width: 522px;
height: 82px;
border-radius: 6px;
border: 1px solid #191919;
background: #191919;
color: rgba(255, 255, 255, 0.70);
font-size: 24px;
line-height: 28.8px;
padding: 26px 0 26px 19px;
}
.main-4-btn{
width: 87px;
height: 48px;
border-radius: 6px;
background: #118DA8;
color: rgba(255, 255, 255, 0.70);

font-family: "DMB";
font-size: 15px;
font-weight: 700;
line-height: 28.8px;
}
</style>