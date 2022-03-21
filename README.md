<!DOCTYPE html>

<html lang="en">

<head>
  
    <meta charset="UTF-8">
    <meta name="description" content="Security Is Just An Illusion Babe">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="https://cdn.discordapp.com/attachments/912533918371184700/924410235433676800/rwq.png">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Iceland&display=swap" rel="stylesheet">
    <link href="//db.onlinewebfonts.com/c/3b7290809525cf2c604896711e04c9fe?family=Pixel+Operator+Mono+8" rel="stylesheet" type="text/css"/>
    <title>Hacked by Cyber Dark Crew </title>
</head>
<body>
<center>
<br><br>
    <img src="https://cdn.discordapp.com/attachments/912533918371184700/924410235433676800/rwq.png" alt="logo" height="200" width="200"><br>
    <font class="Name" color="#ff0000">&#9957 <font class="Name" color="#d9d9d9">Hacked BY Cyber<font color="red">D<font color="#d9d9d9">ark <font class="Name" color="#ff0000">&#9957;</font><BR>
    <font font-face="mur7t3" size="5" color="#ff0000">[!] SITE SECURITY BREACHED [!]</font><br>
    <font class="msg" size="5" color="#f2f2f1">Fuck You Admin  <br> FUCK THE SYSTEM</font><br>
    
    <font class="hash" color="red">#<font class="bhs" color="#f2f2f1"> Mr.Dark Was Here!!!</font><br><br>
    
    <div class="box">
        <i><marquee scrollamount="8"><font face="mur7t3" size="5" color="red"># <font font-face="mur7t3" size="4" color="#FFFFFF">| Mr.Dark | NSWBOY |  Hosin Sasuke | Kenan | Omar | Whisper | Hota | Rashid | E. I. Andrews</marquee></i>
    </div><br>
    <audio id="myaudio">
        <source src="https://c.top4top.io/m_2076j732g0.mp3" type="audio/ogg">
        <source src="https://c.top4top.io/m_2076j732g0.mp3" type="audio/mpeg">
    </audio>

   
    <button class="btn" onclick="playAudio()" type="button">PLAY</button>
    <font><------<a href="https://www.facebook.com/CyberDarkCrew" ><button class="conbtn">Contact</button></a>------></font>
    <button class="btn" onclick="pauseAudio()" type="button">STOP</button><br><br>


<script type="text/javascript">
    (function(){
    var global = this;
    var globalName = 'starField';
    var numberOfStars = 90;
    var depthDimentsion = 2000;
    var viewingDepth = 0.0001;
    var forwardVelocity = 0.3;
    var d = depthDimentsion*(viewingDepth/100);
    var planeDepth = depthDimentsion - d;
    var fv = planeDepth*(forwardVelocity/100);
    var zMultiplier = (depthDimentsion)/d;
    var starObjs, starHTML;
    var posMod, sy, sx, windowCenterY, windowCenterX;
    var scaleXAdjust, scaleYAdjust;
    if((document.layers)&&(this.Layer)){
      starHTML = [
      '<layer id=\"stars','',
      '\" left=\"0\" top=\"0\" width=\"1\" height=\"1"',
      ' bgColor=\"#FFFFFF\"><\/layer>'];
    }else{
      starHTML = [
      '<div id="stars','',
      '" style="position:absolute;width:1px;overflow:',
      'hidden;height:1px;background-color:#FFFFFF;',
      'font-size:1px"><\/div>'];
    }
    function compatModeTest(obj){
      if((document.compatMode)&&
         (document.compatMode.indexOf('CSS') != -1)&&
         (document.documentElement)){
        return document.documentElement;
      }else if(document.body){
        return document.body;
      }else{
        return obj;
      }
    }
    function getWindowState(){
      var global = this;
      var readScroll = {scrollLeft:NaN,scrollTop:NaN};
      var readSizeC = {clientWidth:NaN,clientHeight:NaN};
      var readSizeI = {innerWidth:NaN,innerHeight:NaN};
      var readScrollX = 'scrollLeft';
      var readScrollY = 'scrollTop';
      function getWidthI(){return readSizeI.innerWidth;}
      function getWidthC(){return readSizeC.clientWidth|0;}
      function getHeightI(){return readSizeI.innerHeight;}
      function getHeightC(){return readSizeC.clientHeight|0;}
      function getHeightSmart(){
          return retSmaller(getHeightI(), getHeightC());
      }
      function getWidthSmart(){
          return retSmaller(getWidthI(), getWidthC());
      }
      function setInnerWH(){
        theOne.getWidth = getWidthI;
        theOne.getHeight = getHeightI;
      }
      function retSmaller(inr, other){
        if(other > inr){
          setInnerWH();
          return inr;
        }else{
          return other;
        }
      }
      var theOne = {
        getScrollX:function(){return readScroll[readScrollX]|0;},
        getScrollY:function(){return readScroll[readScrollY]|0;},
        getWidth:getWidthC,
        getHeight:getHeightC
      };
      function main(){return theOne;}
      function rankObj(testObj){
        var dv,dhN;
        if(testObj&&(typeof testObj.clientWidth == 'number')&&
           (typeof testObj.clientHeight == 'number')){
          if(((dv = global.innerHeight - testObj.clientHeight) >= 0)&&
             ((dh = global.innerWidth - testObj.clientWidth) >= 0)){
            if(dh == dv){
              return 0;
            }else if((dh&&!dv)||(dv&&!dh)){
              return (dh+dv);
            }
          }
        }
        return NaN;
      }
      if((typeof global.innerHeight == 'number')&&
         (typeof global.innerWidth == 'number')){
        readSizeI = global;
        var bodyRank = rankObj(document.body);
        var rankDocEl = rankObj(document.documentElement);
        var selEl = null;
        if(!isNaN(bodyRank)){
          if(!isNaN(rankDocEl)){
            if(bodyRank < rankDocEl){
              selEl = document.body;
            }else if(bodyRank > rankDocEl){
              selEl = document.documentElement;
            }else{
              selEl = compatModeTest(document.body);
            }
          }else{
            selEl = document.body;
          }
        }else if(!isNaN(rankDocEl)){
          selEl = document.documentElement;
        }
        if(selEl){
          readSizeC = selEl
          theOne.getWidth = getWidthSmart;
          theOne.getHeight = getHeightSmart;
        }else{
          setInnerWH();
        }
      }else{
        readSizeC = compatModeTest(readSizeC);
      }
      if((typeof global.pageYOffset == 'number')&&
         (typeof global.pageXOffset == 'number')){
        readScroll = global;
        readScrollY = 'pageYOffset';
        readScrollX = 'pageXOffset';
      }else{
        readScroll = compatModeTest(readScroll);
      }
      return (getWindowState = main)();
    }
    var windowState = getWindowState();
    function readWindow(){
      scaleYAdjust = (((windowCenterY =
              (windowState.getHeight() >>1)) - 16)*
                           zMultiplier);
      scaleXAdjust = (((windowCenterX =
              (windowState.getWidth() >> 1)) - 16)*
                          zMultiplier);
      sy = windowCenterY + windowState.getScrollY();
      sx = windowCenterX + windowState.getScrollX();
    }
    function getStyleObj(id){
      var obj = null;
      if(document.getElementById){
        obj = document.getElementById(id);
      }else if(document.all){
        obj = document.all[id];
      }else if(document.layers){
        obj = document.layers[id];
      }
      return ((typeof obj != 'undefined')&&
          (typeof obj.style != 'undefined'))?
                      obj.style:obj;
    }
    function starObj(id, parent, prv){
      var next,reset;
      var divClip, div = getStyleObj("stars"+id);
      var y,x,z,v,dx,dy,dm,dm2,px,py,widthPos,temp;
      (reset = function(){
        px = Math.random()<0.5 ? +1 : -1;
        py = Math.random()<0.5 ? +1 : -1;
        y = ((Math.random()*Math.random()*
            scaleYAdjust)+windowCenterY);
        x = ((Math.random()*Math.random()*
            scaleXAdjust)+windowCenterX);
        widthPos = (x + zMultiplier);
        z = 0;
      })();
      z = Math.random()*planeDepth*0.8;
      function step(){
        temp = x * (v = d/(depthDimentsion - z));
        dm = ((dm2 = ((widthPos * v)-temp)|0)>>1);
        dy = (y * v);
        dx = (temp);
      }
      if(div){
        if(!posMod){
          posMod = (typeof div.top == 'string')?'px':0;
        }
        divClip =  ((typeof div.clip != 'undefined')&&
                 (typeof div.clip != 'string'))?
                         div.clip:div;
        this.position = function(){
          step();
          if(((z += fv) >= planeDepth)||
             ((dy+dm) > windowCenterY)||
            ((dx+dm) > windowCenterX)){
            reset();
            step();
            dm = 0;
          }
          div.top = ((sy+(py*dy)-dm)|0)+posMod;
          div.left = ((sx+(px*dx)-dm)|0)+posMod;
          divClip.width = (divClip.height = dm2+posMod);
          next.position();
        };
      }else{
        this.position = function(){return;};
      }
      if(++id < numberOfStars){
        next = new starObj(id, parent)
      }else{
        next = parent
      }
    }
    function init(){
      if(!getStyleObj("stars"+(numberOfStars-1))){
        setTimeout(starField, 200);
      }else{
        readWindow();
        starObjs = new starObj(0, init);
        init.act();
      }
    };
    init.position = function(){return;}
    init.act = function(){
      readWindow();
      starObjs.position();
      setTimeout(init.act,50);
    };
    init.act.toString = function(){
      return globalName+'.act()';
    };
    init.toString = function(){
      while(global[globalName])globalName += globalName;
      global[globalName] = this;
      return globalName+'()';
    };
    for(var c = numberOfStars;c--;){
      starHTML[1] = c;
      document.write(starHTML.join(''));
    }
    setTimeout(init, 200);
  })();

  var x = document.getElementById("myaudio");
  function playAudio() {
    x.play();
  }
  function pauseAudio() {
    x.pause()
  }
</script>

<style type="text/css">
    body {
    background-color: black;
    margin: 0;
    padding: 0;
}

.Name {
    font-family: 'Iceland', cursive;
    font-size:30px;

}

body{ } @font-face { font-family: mur7t3; src: url(https://watchdogsfont.com/font/PixelOperatorMono.ttf); }

.hash {
    font-family: 'Iceland', cursive;
    font-size: 20px;
}

.bhs {
    font-family: 'Iceland', cursive;
    font-size: 25px;
}

.box {
    width: 300px;
}

.grt {
    font-family: 'Iceland', cursive;
    font-size: 20px;
}

.grps {
    font-family: 'Iceland', cursive;
    font-size: 20px;
    text-shadow: 1px 1px #ff0000;
}

.btn {
    font-family: 'Iceland', cursive;
    font-size: 20px;
    height: 30px;
    width: 60px;
    color: white;
    border-radius: 10px 15px;
    border-style: solid;
    border-color: red;
    border-width: 1.5px;
    background: none;
}
</style>

</body>
</html>
