<!DOCTYPE html>
<html>
<head>
  <title>Nyota Fund</title>
  <style>
    body {
      font-family: Arial;
      background: #0b1a2f;
      color: white;
      text-align: center;
      padding-top: 100px;
    }
    .box {
      background: white;
      color: black;
      padding: 20px;
      width: 300px;
      margin: auto;
      border-radius: 10px;
    }
    input {
      width: 90%;
      padding: 10px;
      margin: 10px 0;
    }
    button {
      padding: 10px;
      width: 100%;
      background: #007bff;
      color: white;
      border: none;
    }
  </style>
</head>
<body>

<h1>Nyota Fund</h1>

<div class="box">
  <h3>Login</h3>
  <input type="text" placeholder="Username">
  <input type="password" placeholder="Password">
  <button onclick="login()">Login</button>
</div>

<script>
function login() {
  alert("Login successful (Demo)");
}
</script>

</body>
</html>
