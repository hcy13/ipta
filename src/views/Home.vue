<template>
    <div class="home">
    <img class="back" src="https://raw.githubusercontent.com/hcy13/ipta/master/photo/IMG_6815.PNG">
    
    <div class="upper">
    <div class="sch">
      <p>國立清華大學藝術學院</p>
    </div>
    </div>
    <div class="box"><div class="head">藝術學院學士班</div><img class="photo" src="http://ipta.nthu.edu.tw/wp-content/themes/hestia/assets/img/slider2.jpg">
    
    </div>


    <div class="under">
      <div class="down">
        <p class="aa">國立清華大學藝術學院</p>
      </div>
      <div class="adress">
        <p>國立清華大學藝術學院學士班
  30014新竹市南大路521號（教學大樓3F）</p>
      </div>
      <div class="tel">
        <p class="hi">+886-3-5715131 #78802 ipta@my.nthu.edu.tw/ </p>
      </div>
    </div>

    </div>
</template>

<style>

body{
    background-color: black;
}
.back{
  position: fixed;
  left:0px;
  top:-100px;
  width:100%;
  z-index: -1000;
}
.box{
    width:100%;
    height:500px;
}
.upper{
  width: 100%;
  height: 80px;
  padding-left: 0px;
  background: rgba(52, 47, 47, 0.7);
  z-index: 0;
  padding-top:0px;
}
.sch{
  width: 226px;
  height: 28px;
  left: 122px;
  padding-top: 12px;

  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color:white;
}

.photo{
    padding-top:30px;
    width:100%;
    top:500px;
    z-index: -10;
}
.down{
  width:200px;
  height: 0px;
  left: 121px;
  padding-top:0px;
  padding-right:0;

  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 21px;
  text-align: center;

  color: #FFFFFF;
}
.adress{
    position:absolute;
    width:200px;
  height: 20px;
  padding-left: 234px;
  padding-top: 0;

  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 21px;

  color: #FFFFFF;
}
.tel{
    width:150px;
  height: 5px;
  padding-left: 450px;
  top:-10px;

  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 21px;

  color: #FFFFFF;
}
.head{
    z-index: 100;
    position:absolute;
}
</style>