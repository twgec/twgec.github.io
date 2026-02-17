---
title: 台電外線進度查詢
date: 2021-08-19 13:26:57
---
<script type="text/javascript">
function SetCwinHeight(){
  var iframeid = document.getElementById("iframeid"); //iframe id
  if (document.getElementById) {
    if (iframeid && !window.opera) {
      if (iframeid.contentDocument && iframeid.contentDocument.body.offsetHeight) {
        iframeid.height = iframeid.contentDocument.body.offsetHeight + 50;
      } else if (iframeid.Document && iframeid.Document.body.scrollHeight) {
        frameid.height = iframeid.Document.body.scrollHeight + 50;
      }
    }
  }
}
</script>

<iframe width="100%" id="iframeid" onload="Javascript:SetCwinHeight()" scrolling=no height="2000" frameborder="0" src="https://wapp.taipower.com.tw/newnas/nawp090.aspx"></iframe>

