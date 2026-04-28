<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nyota Fund</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(to right, #0d6efd, #0a58ca);
  color: white;
}

header {
  text-align: center;
  padding: 20px;
}

.container {
  max-width: 400px;
  margin: auto;
  background: white;
  color: black;
  padding: 20px;
  border-radius: 10px;
}

input {
  width: 100%;
  padding: 10px;
  margin-top: 10px;
  margin-bottom: 15px;
  border-radius: 6px;
  border: 1px solid #ccc;
}

button {
  width: 100%;
  padding: 12px;
  background: #0d6efd;
  color: white;
  border: none;
  border-radius: 6px;
  font-size: 16px;
}

.info {
  text-align: center;
  margin-top: 20px;
}
</style>
</head>

<body>

<header>
  <h1>Nyota Fund</h1>
  <p>Fast & Reliable Loans</p>
</header>

<div class="container">
  <h2>Login</h2>

  <input type="text" placeholder="Phone Number">
  <input type="password" placeholder="Password">

  <button onclick="alert('Login feature coming soon')">Login</button>

  <div class="info">
    <p>New user?</p>
    <button onclick="alert('Registration fee is Ksh 100')">
      Register (Ksh 100)
    </button>
  </div>
</div>

</body>
</html>
