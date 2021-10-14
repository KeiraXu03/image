# image
<SPAN style="FONT-SIZE: 18px"><html> 
<head> 
<style type="text/css"> 
  .TopDIV  
  {   
     position:absolute;  
     left:130px; 
     top:10px; 
     width:105; 
     height:30; 
     overflow-x:hidden; 
     overflow-y:auto; 
     float: right; 
     border-style.:solid; 
     border-width:;  
     border-color:red 
  } 
  .LeftDIV  
  {   
     position:absolute;  
     left:10px; 
     top:40px; 
     width:120; 
     height:60; 
     overflow-x:hidden; 
     overflow-y:hidden; 
     float: right; 
     border-style.:solid; 
     border-width:;  
     border-color:yellow 
  } 
  .MainDIV  
  {   
     position:absolute;  
     left:130px; 
     top:40px; 
     width:120;; 
     height:80; 
     overflow-x:auto; 
     overflow-y:auto; 
     float: right; 
     border-style.:solid; 
     border-width:;  
     border-color:blue 
  } 
</style> 
<script type="text/javascript" language="javascript"> 
function setStyle() 
{ 
//145的由来LeftDiv的left+width+15（15是滚动条的宽度） 
document.getElementById("a").style.width=document.body.clientWidth - 145; 
//130的由来LeftDiv的left+width 
document.getElementById("c").style.width=document.body.clientWidth - 130; 
//55的由来TopDIV的top+height+15（15是滚动条的宽度） 
document.getElementById("b").style.height=document.body.clientHeight - 55; 
//40的由来TopDIV的top+height 
document.getElementById("c").style.height=document.body.clientHeight - 40; 
} 
</script> 
  
</head> 
<body onresize="setStyle();" onLoad="setStyle();"> 
  
<div id='a' class="TopDIV"> 
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
</div> 
  
<div id='b' class="LeftDIV"> 
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
3234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
4234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
5234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
6234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
7234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
8234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
9234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
0234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
</div> 
<div id='c' onscroll="document.getElementById('b').scrollTop = this.scrollTop;document.getElementById('a').scrollLeft = this.scrollLeft;"  
 class="MainDIV"> 
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
3234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
4234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
5234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
6234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
7234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
8234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
9234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
0234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ 
</div> 
</body> 
</html> 
</SPAN> 

<html>
<head>
<style type="text/css">
  .TopDIV
  { 
     position:absolute;
     left:130px;
     top:10px;
     width:105;
     height:30;
     overflow-x:hidden;
     overflow-y:auto;
     float: right;
     border-style.:solid;
     border-width:;
     border-color:red
  }
  .LeftDIV
  { 
     position:absolute;
     left:10px;
     top:40px;
     width:120;
     height:60;
     overflow-x:hidden;
     overflow-y:hidden;
     float: right;
     border-style.:solid;
     border-width:;
     border-color:yellow
  }
  .MainDIV
  { 
     position:absolute;
     left:130px;
     top:40px;
     width:120;;
     height:80;
     overflow-x:auto;
     overflow-y:auto;
     float: right;
     border-style.:solid;
     border-width:;
     border-color:blue
  }
</style>
<script type="text/javascript" language="javascript">
function setStyle()
{
//145的由来LeftDiv的left+width+15（15是滚动条的宽度）
document.getElementById("a").style.width=document.body.clientWidth - 145;
//130的由来LeftDiv的left+width
document.getElementById("c").style.width=document.body.clientWidth - 130;
//55的由来TopDIV的top+height+15（15是滚动条的宽度）
document.getElementById("b").style.height=document.body.clientHeight - 55;
//40的由来TopDIV的top+height
document.getElementById("c").style.height=document.body.clientHeight - 40;
}
</script>
 
</head>
<body onresize="setStyle();" onLoad="setStyle();">
 
<div id='a' class="TopDIV">
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
</div>
 
<div id='b' class="LeftDIV">
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
3234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
4234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
5234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
6234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
7234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
8234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
9234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
0234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
</div>
<div id='c' onscroll="document.getElementById('b').scrollTop = this.scrollTop;document.getElementById('a').scrollLeft = this.scrollLeft;"
 class="MainDIV">
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
3234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
4234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
5234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
6234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
7234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
8234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
9234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
0234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
2234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ
</div>
</body>
</html>
