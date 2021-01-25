<template>
      

    <div class='news'>
        <div class="upper">
            <div class="sch">
      <p>國立清華大學藝術學院</p>
        </div>
        </div>
        <div class="mid">
    <h2>院學士班最新訊息</h2>
    <img class="img1" src="https://ipta.nthu.edu.tw/wp-content/uploads/2020/04/5e7987.jpg">
    <div class="text1">
        <p>【獲獎】《那顆Ｇ1咻！》國立清華大學藝術學院學士班第一屆系展 得獎名單</p>
    </div>
    <img class="img2" src="https://ipta.nthu.edu.tw/wp-content/uploads/2020/04/5e7987.jpg">
    <div class="text2">
        <p>【獲獎】2020春之清華 – 藝術卓越獎 科技藝術類 得獎名單</p>
    </div>
    <img class="img3" src="https://ipta.nthu.edu.tw/wp-content/uploads/2020/04/5e7987.jpg">
    <div class="text3">
        <p>【徵件公告】春之清華—藝術卓越獎科技藝術類 甄選辦法</p>
    </div>
    <img class="img4" src="https://ipta.nthu.edu.tw/wp-content/uploads/2020/04/5e7987.jpg">
    <div class="text4">
        <p>《那顆Ｇ1咻！》國立清華大學藝術學院學士班第一屆系展</p>
    </div>
    <img class="img5" src="https://ipta.nthu.edu.tw/wp-content/uploads/2020/04/5e7987.jpg">
    <div class="text5">
        <p>國立清華大學 藝術學院學士班 徵聘【助理教授級以上】專任教師1名</p>
    </div>
    <img class="img6" src="https://ipta.nthu.edu.tw/wp-content/uploads/2020/04/5e7987.jpg">
    <div class="text6">
        <p>【獲獎】2020藝術學院學士班春之清華獎學金 獲獎名單</p>
        
    </div>
<el-carousel height="200px" direction="vertical" :autoplay="false">
    <el-carousel-item v-for="item in 3" :key="item">
      <h3 class="medium">{{ item }}</h3>
    </el-carousel-item>
  </el-carousel>
    </div>

    <div class="under">
        <div class="down">
        <p>國立清華大學藝術學院</p>
        </div>
        <div class="adress">
        <p>國立清華大學藝術學院學士班
    30014新竹市南大路521號（教學大樓3F）</p>
        </div>
        <div class="tel">
        <p>+886-3-5715131 #78802 / </p>
        </div>
        <div class="email">
        <p>ipta@my.nthu.edu.tw</p>
        </div>
    </div>
    </div>
</template>

<style>
body{
    background-color: black;
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
.upper{
    width: 100%;
    height: 80px;
    left: 0px;
    top: 0px;
    z-index: 0;
    background: rgba(52, 47, 47, 0.7);
}
.mid{
    height: 2030px;
    left: 62px;
    top: 237px;
    z-index: 0;
    background: rgba(52, 47, 47, 0.7);
}
.under{
    width: 100%;
    height: 198px;
    left: 0px;
    bottom: 0px;
    z-index: 0;
    background: rgba(52, 47, 47, 0.7);
}
h2{
    height: 42px;
    left: 648px;
    padding-top: 120px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 42px;

    color: #FFFFFF;
}
.img1{
    position: relative;
    width: 300px;
    height: 150px;
    padding-left:20px;
    padding-top: 50px;
}
.img2{
    position: relative;
    width: 300px;
    height: 150px;
    padding-left:20px;
    padding-top: 50px;
}
.img2{
    position: relative;
    width: 300px;
    height: 150px;
    padding-left:20px;
    padding-top: 50px;
}
.img3{
    position: relative;
    width: 300px;
    height: 150px;
    padding-left:20px;
    padding-top: 50px;
}
.img4{
    position: relative;
    width: 300px;
    height: 150px;
    padding-left:20px;
    padding-top: 50px;
}
.img5{
    position: relative;
    width: 300px;
    height: 150px;
    padding-left:20px;
    padding-top: 50px;
}
.img6{
    position: relative;
    width: 300px;
    height: 150px;
    padding-left:20px;
    padding-top: 50px;
}
.el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 200px;
    margin: 0;
  }
  
  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }
  
  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
.text1{
    height: 16px;
    left: 57px;
    top: 884px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;

    color: #FFFFFF;
}
.text2{
    height: 16px;
    left: 57px;
    top: 884px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;

    color: #FFFFFF;
}
.text3{
    height: 16px;
    left: 907px;
    top: 884px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;

    color: #FFFFFF;
}
.text4{
    height: 16px;
    left: 57px;
    top: 1236px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;

    color: #FFFFFF;
}
.text5{
    height: 16px;
    left: 670px;
    top: 1236px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;

    color: #FFFFFF;
}
.text6{
    height: 16px;
    left: 57px;
    top: 1590px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;

    color: #FFFFFF;
}
.down{
    width: 226px;
    height: 28px;
    left: 121px;
    top: 943px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 21px;
    text-align: center;

    color: #FFFFFF;
}
.adress{
    width: 335px;
    height: 42px;
    left: 584px;
    top: 932px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 21px;

    color: #FFFFFF;
}
.tel{
    width: 169px;
    height: 21px;
    left: 1128px;
    top: 957px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 21px;

    color: #FFFFFF;
}
.email{
    width: 169px;
    height: 21px;
    left: 1128px;
    top: 957px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 21px;

    color: #FFFFFF;
}
</style>