<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Page</title>
<style>
  body {
    font-family: 'Arial', sans-serif;
    background-image: url('path-to-your-background-image.jpg');
    background-size: cover;
  }
  .login-container {
    width: 300px;
    margin: 100px auto;
    padding: 20px;
    background: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  input[type="text"], input[type="password"] {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
    border-radius: 5px;
  }
  .login-container button {
    width: 100%;
    padding: 10px;
    background-color: #5cb85c;
    border: none;
    border-radius: 5px;
    color: white;
    cursor: pointer;
  }
  .login-container button:hover {
    background-color: #4cae4c;
  }
</style>
</head>
<body>

<div class="login-container">
  <h2>Log in</h2>
  <form action="/submit-login" method="post">
    <input type="text" placeholder="Enter your username or email" name="username" required>
    <input type="password" placeholder="Enter your password" name="password" required>
    <div>
      <label><input type="checkbox" name="remember"> Remember me</label>
    </div>
    <button type="submit">Sign in</button>
    <a href="/forgot-password">Forgot password?</a>
  </form>
</div>

</body>
</html>
