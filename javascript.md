# Offer-First-Visit-No-Redirect-then-redirect-always-
If you have a offer for people you can say it is for first visit only If you leave it you will never be able to get it again. On all 2nd and visits after that by same user it will redirect to home page or some other page.


<script type="text/javascript">
function redirect(){
var thecookie = readCookie('doRedirect');
if(!thecookie){
}
  else{
    //This is the place for your configration
    //Just put link where you want to redirect
    window.location = 'https://vincent.clickfunnels.com/capture-light289ofqpx';
  }
}
  function createCookie(name,value,days){
    if (days){
      var date = new Date();
      date.setTime(date.getTime()+(days*24*60*60*1000));
      var expires = "; expires="+date.toGMTString();
    }
    else var expires = "";
    document.cookie = name+"="+value+expires+"; path=/";
  }
  function readCookie(name){
    var nameEQ = name + "=";
    var ca = document.cookie.split(';');
    for(var i=0;i < ca.length;i++)
    {
      var c = ca[i];
      while (c.charAt(0)==' ') c = c.substring(1,c.length);
      if (c.indexOf(nameEQ) == 0)
        return c.substring(nameEQ.length,c.length);
    }
    return null;
  }
  window.onload = function(){
    redirect();
   createCookie('doRedirect','true','999');
}
</script>
