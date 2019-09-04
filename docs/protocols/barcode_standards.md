<meta http-equiv="refresh" content="5;url=https://docs.shophumm.com.au/pos/getting-started/" />

<div id="redirect-text" style="text-align:center">
    <h1><span>posdocs</span> moved to <span>docs.shophumm.com.au</span></h1>
    <p>You will be re-directed in <span id="countdown">5</span> seconds ...</p>
</div>

<script language="javascript">
var max_time = 5;
var cinterval;
 
function countdown_timer(){
  // decrease timer
  max_time--;
  document.getElementById('countdown').innerHTML = max_time;
  if(max_time == 0){
    clearInterval(cinterval);
  }
}
// 1,000 means 1 second.
cinterval = setInterval('countdown_timer()', 1000);
</script>