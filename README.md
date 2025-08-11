<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login Page</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f1f1f1; }
    .login-box {
      width: 300px; margin: 80px auto; padding: 30px 25px;
      background: #fff; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .login-box h2 { text-align: center; margin-bottom: 20px; }
    .login-box input[type="text"], .login-box input[type="password"] {
      width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 4px;
    }
    .login-box button {
      width: 100%; padding: 10px; background: #3498db; border: none; color: #fff;
      border-radius: 4px; font-size: 16px; cursor: pointer;
    }
    .login-box button:hover { background: #2980b9; }
  </style>
</head>
<body>
  <div class="login-box">
    <h2>Login</h2>
    <form action="/login" method="post">
      <input type="text" name="username" placeholder="Username" required>
      <input type="password" name="password" placeholder="Password" required>
      <button type="submit">Login</button>
    </form>
  </div>
</body>
</html>
