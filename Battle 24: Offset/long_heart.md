
![long heart](https://user-images.githubusercontent.com/43888129/229336761-b5dfb184-75bc-4a05-997a-ccdf0f788c3d.png)



```html
<div></div>
<p></p>
<style>
  body{
    background:#62306D;
    margin: 0;
  }
  div, p{
    width: 75px;
    height: 200px;
    bottom: 0;
    position: absolute;
    background: #F7EC7D;
    border-radius: 100px 100px 0 0;
  }
  div::after{
    content: "";
    position: absolute;
    height: 37px;
    width:37px;
    background:#62306D;
    right:-38;
    top:87;
    border-radius:100px;
  }
  div::before{
    content: "";
    position: absolute;
    height: 20px;
    width:20px;
    background:#F7EC7D;
    left: 75;
    top: 105;
  }
  p{
    width: 200px;
    height: 75px;
    margin: 0;
    border-radius: 100px
  }
</style>

```
