# FinalProjectFINAL<!DOCTYPE html>
<html lang="en">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<head>
<title>Final project</title>
<link href="FinalProject.CSS" rel="stylesheet">
</head>
<body>
 <header class="C1" >Contact Me</header>
<div class="Containor">

<p class="o">Hey, how you doin' today? to make you feel better just visit this website
  <a href="https://osamaosb.github.io/FinalProjectB/" > Just click here and enjoy...</a>
</p>

    <label for="object">Subject*</label>
    <input type="text" class="Os" id="Subject1" name="subject" placeholder="your subject is.." >

     <label for="Email">Email*</label>
     <input type="text" class="Os" id="Email1" name="Email" placeholder="Your Email is..">

     <label for="id">ID*</label>
     <input type="text" class="Os" id="ID1" name="id" placeholder="Your ID is..">

     <label for="URL">URL*</label>
     <input type="text" class="Os" id="URL1" name="URL" placeholder="Your URL is..">


     <label for="Message">Message</label>
     <textarea name="Message" class="Os" id="Message1" placeholder="Write your messagge for us.."></textarea>

     <input type="submit" id="L" value="Submit" onclick="return foo();" >
<script type="text/javascript">
function foo() {




  var s="hi", n=2;
  var x1 = document.getElementById("Subject1").value;
  var x2 = document.getElementById("Email1").value;
  var x3 = document.getElementById("ID1").value;
  var x4 = document.getElementById("URL1").value;
  var x5 = document.getElementById("Message1").value;
  var x6 = x1.toString();
  var x7 = x2.toString();
  var x8 = x3.toString();
  var x9 = x4.toString();
  var x10 = x5.toString();


/*  if (Number (document.getElementById("Subject1").value) === "NaN"){

    alert("What the Fuck");
  }*/

   if (x1 == "")  alert("The Subject field is empty!");
   if (x2 == "") {
       var F1 = "empty" ;
      alert("The Email field is empty!");
    }
   if (x3 == "")  alert("The ID field is empty!");
   if (x4 == "")  {
 var F2 = "empty" ;
     alert("The URL field is empty!");
}
   if (x5 == "")  alert("The Message field is empty!");
var l1 = x1.length;
var l2 = x2.length;
var l3 = x3.length;
var l4 = x4.length;
var l5 = x5.length;

var sum1=0;
var sum2=0;
var sum3=0;

for (i = 0 ; i< l1 ;  i++){
   if (x6[i]==0 || x6[i]==1 ||x6[i]==2 ||x6[i]==3 ||x6[i]==4 ||x6[i]==5 ||x6[i]==6 ||x6[i]==7 ||x6[i]==8 ||x6[i]==9 ){

     sum1 = sum1 +1;
   }
 }
   if (sum1 >0  ) {alert ("Subject field is NOT a string, please enter a valid string");}

   for (i = 0 ; i< l5 ;  i++){
      if (x10[i]==0 || x10[i]==1 ||x10[i]==2 ||x10[i]==3 ||x10[i]==4 ||x10[i]==5 ||x10[i]==6 ||x10[i]==7 ||x10[i]==8 ||x10[i]==9 ){

        sum2 = sum2 +1;
      }
    }
      if (sum2 >0  ) { alert ("Message field is NOT a string, please enter a valid string");}


for (i =0 ; i<l3 ; i++){
   if ( x8[i] !=0 && x8[i]!=1 && x8[i]!=2 && x8[i]!=3 && x8[i]!=4 && x8[i]!=5 && x8[i]!=6 && x8[i]!=7 && x8[i]!=8 && x8[i]!=9 && x3 != "") {
     sum3 = sum3 +1 ;
   }
}

if (sum3 > 0){
     alert ("ID field is NOT a Number, please enter a valid Number");
   }


var pos = x7.search("@");
var EMAIL = x7.slice(pos, l2);
if (F1!="empty"){
alert(EMAIL);
}
   var US = l4-10
   var USERNAME = x9.slice(0, US);
   if (F2!="empty"){
     alert( USERNAME);
}
}

</script>




</div>

<footer class="C1">@ copy Right 2020</footer>
</body>
