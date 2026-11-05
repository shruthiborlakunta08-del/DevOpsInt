# DevOpsInt<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Register</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 400px;
      margin: 3rem auto;
      padding: 0 1rem;
    }

    label {
      display: block;
      margin-top: 1rem;
    }

    input, button {
      box-sizing: border-box;
      width: 100%;
      padding: 0.7rem;
      margin-top: 0.3rem;
    }

    button {
      margin-top: 1.5rem;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Create an account</h1>

  <form action="/register" method="post">
    <label for="name">Name</label>
    <input id="name" name="name" autocomplete="name" required>

    <label for="email">Email</label>
    <input id="email" name="email" type="email"
           autocomplete="email" required>

    <label for="password">Password</label>
    <input id="password" name="password" type="password"
           autocomplete="new-password" minlength="8" required>

    <button type="submit">Register</button>
  </form>
</body>
</html>
