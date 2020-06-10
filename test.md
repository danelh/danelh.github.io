<!DOCTYPE HTML>
<html>

<body>

  <p>Before the script...</p>
  
  <script language="JavaScript" type="text/javascript" src="/js/jquery-1.2.6.min.js"></script>
  <script language="JavaScript" type="text/javascript" src="/js/jquery-ui-personalized-1.5.2.packed.js"></script>
  <script language="JavaScript" type="text/javascript" src="/js/sprinkle.js"></script>

  <script>
    var verbs = $.getJSON("test.json", function(json) {
    console.log(json); // this will show the info it in firebug console
});
  </script>

  <p>...After the script_1.</p>

</body>

</html>
