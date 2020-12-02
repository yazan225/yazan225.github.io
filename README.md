<head>
  <link href='https://fonts.googleapis.com/css?family=Varela+Round' rel='stylesheet' type='text/css'>
 <link rel="stylesheet" type="text/css" href="external.css">
 
   <style>
.container {
            width: 400px;
            margin: 50px auto;
        }
.button {
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: right;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
.button1 {
  background-color: white; 
  color: black; 
  border: 2px solid #4CAF50;
}

.button1:hover {
  background-color: green;
  color: white;
}
#container {
text-align:right
}


</style>

</head>
<body>

<div id="container">
<button onclick="myfun()" class="button1 button">Print My CV</button>
</div>
  
  
<h1 onclick="dosomething()">Yazan Salileh</h1>
<hr>
<h3 title="outline" title="" >Summary Of Me : </h3>
<p> my name is yazan, i study at an najah national university
 in the second year and my specialization
 is network and information security ,
 i have a big passion for cyber security 
 and i belive in my self that i want to be in the top level in this feilde,
 To be able to stop the hacker you must learn his method .. and i will dooo</p>
<hr>


<h3 title="Explore me ">My accounts :</h3>
<p><a href="https://www.linkedin.com/in/yazan-salileh-2954381b2/"> my LINKEDIN account</a></p>

<p><a href="https://twitter.com/yazansalileh"> my TWITTER account</a></p>
<hr>
<h3 title="pleasure your eyes " > My Image : </h3>
<img src="119517263_2822506641319441_5874867198165043417_n.jpg" width="500" height="600">
<hr>
<h3 title="Certificate Obtained " >education background : </h3>
<div class="container">

<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * bachelor's degree in NETWORK and INFORNATION SECURITY </p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * high school education degree </p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * Google IT Support </p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * Introduction to Cybersecurity Tools and Cyber Attacks</p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * Technical Support Fundamentals</p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)"> * The Bits and Bytes of Computer Networking </p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * Operating Systems and You: Becoming a Power User </p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * System Administration and IT Infrastructure Services </p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" > * IT Security: Defense against the digital dark arts </p>
<p  onmouseover="changeColor(this)" onmouseout="changeColor(this)" >* ICDL </p>

</div>
<hr>
<h3 title="or volunteer in " > work experiences :</h3>
<p> * softech company</p>
<p> * IEEE </p>
<p> * وحدة تنمية الكفاءات </p> 
<hr>
<h3 title="Enrich Yourself" > hobbies :</h3>
<p> * Networking</p>
<p> * Information Security</p>
<p> * Security</p>
<p> * Google Cloud</p>
<p> * Social Engneering</p>
<p> * AWS</p>
<p> * Cryptograpy</p>
<p> * Block Chain</p>
<p> * Cyber Security</p>
<p> * Chess</p>
<p> * Table tennis</p>
<p> * Oparating system</p>
<p> * Software</p>
<p> * Hardware</p>
<p> * Scripting</p>
<p> * Network security</p>
<p> * Penetration testing </p>

<script type ="text/javascript">
function dosomething (){
alert ("Welcome, please let me know if you have any questions")
}
      function changeColor(obj) {
            if (obj.style.color == 'red') {
                obj.style.color = 'black';
            } else {
                obj.style.color = 'red';
            }
        }
        function myfun(){
         window.print();
         }
   
</script>
</body>
</html>
