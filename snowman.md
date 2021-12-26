<div class="neck"></div>
<div class="snow"></div>
<div class="eye1"></div>
<div class="eye2"></div>
<div class="hat"></div>
<style>
  body{
    background: #AC474B;
  }
  .hat{
    background: linear-gradient(#0E1F2B 34%, #FFFFFF 33%,#FFFFFF 55%,#0E1F2B 50%);
    height: 45px;
    width: 40px;
    position: absolute;
    top: 55;
    left: 180
  }
  .hat::after{
    content:"";
    height: 5px;
    width: 60px;
    background: #0E1F2B;
    position:absolute;
    bottom: 0;
    right: -10
  }
  .snow{
    border-radius: 50%;
    height: 100px;
    width: 100px;
    position: absolute;
    background: #ffffff;
    top:145;
    left:150
  }
  .snow::before{
    content:"";
    height: 60px;
    width: 60px;
    border-radius: 50%;
    background: #FFFFFF;
    position:absolute;
    inset: -50px 20px;
  }
  .eye1,.eye2{
    border-radius: 50%;
    height: 10px;
    width: 10px;
    background:#0E1F2B;
    z-index:99;
    position:absolute;
    top:112;
    left: 185;
  }
  .eye2{ 
    left: 205;
  }
  .neck{
    height: 11px;
    width: 60px;
    background:#FFA63F;
    position:absolute;
    border-radius:10px ;
    z-index: 9;
    top: 142;
    left: 170;
  }
  .neck::before,.neck::after{
    content:'';
    height: 4px;
    width: 65px;
    background:#AC474B;
    position:absolute;
    top: -3;
    left:-3;
  }
  .neck::after{
    top: 11
  }
</style>
