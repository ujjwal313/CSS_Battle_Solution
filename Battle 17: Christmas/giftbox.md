![giftbox](https://user-images.githubusercontent.com/43888129/147415599-b7ed6fcf-7fbc-49b4-97d6-8f16f5074195.png)





```

<div class="knot"></div>
<div class="gift"></div>
<style>
  body{background:#AC474B;}
  .knot{
    height: 10px;
    width: 40px;
    background: #ffffff;
    position:absolute;
    top:80;
    left:180;
  }
  .knot::before,.knot::after{
    content:'';
    height:20px;
    width:20px;
    border:10px solid white;
    position:absolute;
    top:-30;
    left:-15;
  }
  .knot::before{
    border-radius:50% 50% 0 50% ;
  }
  .knot::after{
    transform:translateX(30px);
    border-radius:50% 50% 50% 0;
  }
  .gift{
    width:140px;
    height:140px;
    background:white;
    position:absolute;
    top:110;
    left:130;
  }
  .gift::before,.gift::after{
    content:'';
    height:140px;
    width:20px;
    position:absolute;
    background:#AC474B;
    left:60;
  }
  .gift::after{
    transform:rotate(90deg);
  }
</style>

```
