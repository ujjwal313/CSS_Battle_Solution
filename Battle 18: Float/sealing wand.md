
![sealing wand](https://user-images.githubusercontent.com/43888129/163114109-5bfb0a1f-8aa5-4cb7-80f3-53b365ed95c9.png)






```
<div class="center"></div>
<div class="stick"></div>
<div class="feather"></div>
<style>
  body{
    background: #161616;
    display: flex;
    justify-content: center;
    align-items: center
  }
  .center {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    border: 5px #A22015 solid;
    box-shadow:  0 0 0 10px white, 0 0 0 15px #A22015;
    position: relative;
  }
  .center::after{
    content: "";
    position: absolute;
    height: 40px;
    width: 70px;
    background:#E96A23;
    left: 20;
    top:-11;
    z-index: -1;
    border-top-right-radius: 40px;
    border-bottom-right-radius: 5px;
  }
  .center::before{
    content: "";
    position: absolute;
    height: 30px;
    width: 30px;
    background:#A22015;
    top: 35;
    left: -5;
    z-index: -1;
    border-bottom-right-radius: 12px;
    border-bottom-left-radius: 12px;
  }
  .stick{
    width: 20px;
    height: 97px;
    background:#E96A23;
    position: absolute;
    bottom: 0
  }
  .feather{
    width: 36px;
    height: 12px;
    background:white;
    position: absolute;
    left: 145px;
    border-bottom-left-radius: 20px;
  }
  .feather::before{
    content: "";
    width: 52px;
    height: 12px;
    background:white;
    position: absolute;
    left: -15px;
    top:-12px;
    border-bottom-left-radius: 20px;
  }
  .feather::after{
    content: "";
    width: 25px;
    height: 12px;
    background:white;
    position: absolute;
    left: 15px;
    top:12px;
    border-bottom-left-radius: 20px;
  }
</style>
```
