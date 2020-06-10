<!DOCTYPE HTML>
<html>

<body>

  <p>Before the script...</p>
  
  <script src="https://code.jquery.com/jquery-3.5.0.js"></script>
  <script>
    var verbs = $.getJSON({'url': "verbs.json", 'async': false});        
  </script>

  <p>...After the script_9.</p>
  <script>
  // for wait
  //alert("I am an alert box!");
  verbs = verbs.responseJSON;
  console.log(verbs["a"])
  </script>

</body>

</html>
