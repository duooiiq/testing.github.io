<style>
button.result {
background-color: transparent;
border-color: transparent;
}
h4, h3, p {
font-family: "Lucida Sans";
text-align: center;
background-image: linear-gradient(34deg, #b3b3b3, #b3b4b4, #b3b3b3);
}
button {
width: 59px;
}
button.Low {
width: 59px;
}
</style>
<h3>How This Works?</h3>
<p>If You Play HIGH For Gain You Need A Number In 0-4900 If The Number Is More You Lose In Low Is The Same But You Need A Number In 4901-8800</p>
<script type="text/javascript">
function ejemplo2() {
var numal = Math.round(Math.random()*8000);
document.getElementById('upbutton').innerHTML = ( "" +numal);}
</script>
<script type="text/javascript">
function lowmode() {
var numal = Math.round(Math.random()*9000);
document.getElementById('upbutton').innerHTML = ( "" +numal);}
</script>
<div align="center">
<button id="upbutton" class="result">0</button>
</div>
<button onclick="ejemplo2()">High</button>
<div align="right">
<button onclick="lowmode()" class="
Low">Low</button>
</div>
