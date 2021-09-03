<!DOCTYPE html>
<html>

<style>
  .button {
    background-color: orangered;
    border: none;
    color: black;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
  }
</style>



<body style="background-color: black; text-align: center;">

  <h1 style="color: orangered;">Reasons to join One Horn Fanclub</h1>
  <h2 style="color: orangered;">
    <ul">
        <li>He is a firefighter and thus powerful</li>
        <li>He gives many money when defeated, proving his worth</li>
        <li>He is very pretty and would be fun to ride like a horse</li>
    </ul>
    <br>
    <h1>Hopefully these reasons have swayed you!</h2>
  </h2>
  <img src="one horn.png" alt="One Horn in all his glory">
  <h2>
  <button type="button" onclick="crazy()">Click Me!</button>
  </h2>
  <h3 id="crazy" style="color: orangered;">This is will change to show more one horns!</h3>

  <script>
  function crazy() {
    document.getElementById("crazy").innerHTML = "hello";
  }
  </script>

</body>

</html>
