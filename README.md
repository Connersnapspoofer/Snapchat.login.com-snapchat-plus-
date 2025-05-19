# Snapchat.login.com-snapchat-plus-
My clone repository
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Snapchat Login</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --snap-yellow: #fafafa;
      --snap-blue: #00BFFF;
      --card-radius: 18px;
      --input-radius: 8px;
      --shadow: 0 4px 24px rgba(0,0,0,0.13);
    }
    body {
      margin: 0;
      min-height: 100vh;
      background: var(--snap-yellow);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Segoe UI', Arial, sans-serif;
    }
    .login-card {
      background: #fff;
      border-radius: var(--card-radius);
      box-shadow: var(--shadow);
      padding: 2.5rem 2rem 2rem 2rem;
      width: 350px;
      max-width: 94vw;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .logo {
      width: 58px;
      margin-bottom: 1.5rem;
    }
    h2 {
      margin: 0 0 1.5rem 0;
      font-weight: 700;
      font-size: 1.45rem;
      color: #222;
      letter-spacing: 0.01em;
    }
    .input-group {
      width: 100%;
      margin-bottom: 1.2rem;
    }
    input {
      width: 100%;
      padding: 0.85rem 1rem;
      border: 1.5px solid #e0e0e0;
      border-radius: var(--input-radius);
      font-size: 1rem;
      margin-bottom: 0.5rem;
      background: #fafafa;
      transition: border 0.2s;
    }
    input:focus {
      border: 1.5px solid var(--snap-blue);
      outline: none;
      background: #fff;
    }
    .forgot-link {
      display: block;
      text-align: right;
      font-size: 0.97rem;
      color: var(--snap-blue);
      text-decoration: none;
      margin-bottom: 1.2rem;
    }
    .btn-login {
      width: 100%;
      padding: 0.9rem;
      background: var(--snap-yellow);
      color: #222;
      border: none;
      border-radius: var(--input-radius);
      font-weight: 700;
      font-size: 1.08rem;
      cursor: pointer;
      margin-bottom: 1.1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.04);
      transition: background 0.2s;
    }
    .btn-login:hover {
      background: #ffe600;
    }
    .signup-link {
      color: var(--snap-blue);
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
    }
    @media (max-width: 500px) {
      .login-card {
        padding: 1.3rem 0.7rem 1.5rem 0.7rem;
        width: 98vw;
      }
      .logo {
        width: 44px;
      }
      h2 {
        font-size: 1.15rem;
      }
    }
  </style>
</head>
<body>
  <div class="login-card">
    <img class="logo" src="https://upload.wikimedia.org/wikipedia/en/thumb/c/c4/Snapchat_logo.svg/1200px-Snapchat_logo.svg.png" alt="Snapchat Logo">
    <h2>Log in to Snapchat</h2>
    <form>
      <div class="input-group">
        <input type="text" placeholder="Username or Email" required>
      </div>
      <div class="input-group">
        <input type="password" placeholder="Password" required>
      </div>
      <a class="forgot-link" href="#">Forgot Password?</a>
      <button class="btn-login" type="submit">Log In</button>
    </form>
    <div>
      <span>New to Snapchat? </span>
      <a class="signup-link" href="#">Sign up</a>
    </div>
  </div>
</body>
</html>
