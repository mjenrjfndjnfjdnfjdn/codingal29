<html>
  <body>
    <h2>__</h2>
    <h1 id="result"></h1>
    <script>
      async function multiply(a,b) {
        let response = await a * b;
        display(response);
      }
      function display(some) {
        document.getElementById("result").innerHTML = some;
      }
      multiply(5,20);
    </script>
  </body>
</html>
