<!DOCTYPE HTML>
<html>

<body>

  <p>Before the script...</p>

  <script>
    var verbs = $.getJSON("test.json", function(json) {
    console.log(json); // this will show the info it in firebug console
});
  </script>

  <p>...After the script_1.</p>

</body>

</html>
