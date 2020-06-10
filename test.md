<!DOCTYPE HTML>
<html>

<body>

  <p>Before the script...</p>
  
  <script src="https://code.jquery.com/jquery-3.5.0.js"></script>
  <script>
    var verbs = $.getJSON("https://raw.githubusercontent.com/danelh/danelh.github.io/master/verbs.json", function(json) {
    console.log(json); // this will show the info it in firebug console
});
  </script>

  <p>...After the script_4.</p>

</body>

</html>
