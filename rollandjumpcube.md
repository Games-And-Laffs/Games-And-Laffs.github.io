<html>
<h1>Roll and Jump Cube!</h1>
<br>
<script>
window.onload = function() {
    var thegamelink = "https://play.idevgames.co.uk/embed/roll-and-jump-cube";
    var ref = document.referrer;
    var theurl = document.referrer;
    ref = ref.substring(ref.indexOf("://") + 3)
    ref = ref.split("/")[0];
    if(ref == "my-ga.me"){
        theurl = "true"
    } else {
        theurl = "false"
    } 
    document.getElementById("embededGame").src = thegamelink+"/"+theurl;
}
</script>
<div style="position: relative;height: 0;overflow: hidden;padding-bottom: 56.25%;">
    <iframe id="embededGame" src="https://play.idevgames.co.uk/embed/roll-and-jump-cube" width="840px" height="480px" 
    scrolling="no" seamless="seamless" frameBorder="0" style="position: absolute;top:0;left: 0;width: 100%;height: 100%;">Browser not compatible.</iframe>
</div>
<
