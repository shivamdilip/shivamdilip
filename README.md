<!DOCTYPE html>

<html>

<head>

<title>Login Page</title>

<style>

body {

  font-family: sans-serif;

  background-color: #fff;

}

.container {

  width: 500px;

  margin: 0 auto;

  padding: 20px;

  background-color: #f0f0f0;

}

.form-control {

  width: 100%;

  padding: 10px;

  margin-bottom: 10px;

  border: 1px solid #ccc;

}

.btn {

  background-color: #000;

  color: #fff;

  padding: 10px;

  margin-top: 10px;

  border: none;

  cursor: pointer;

}

</style>

</head>

<body>

<div class="container">

  <h1>Login</h1>

  <form action="/login" method="post">

    <div class="form-group">

      <label for="username">Username</label>

      <input type="text" class="form-control" id="username" name="username">

    </div>

    <div class="form-group">

      <label for="password">Password</label>

      <input type="password" class="form-control" id="password" name="password">

    </div>

    <button type="submit" class="btn">Login</button>

  </form>

</div>

</body>

</html>
