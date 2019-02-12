# Fizz-Buzz

<!DOCTYPE html>
<html>
<body>

<h2>Fizz Buzz</h2>

<p id="demo"></p>

<script>

var text = "";
var i;
for (var i = 1; i <= 100; i++) {
  if (i % 3 == 0 && i % 5 == 0) {
  	text += "FizzBuzz" + "<br>";
  }
  else if (i % 3 == 0) {
  	text += "Fizz" + "<br>";
  }
  else if (i % 5 == 0) {
  	text += "Buzz" + "<br>";
  }
  else {
  	text += i + "<br>";
  }
}
document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>
