# SecureMailBank
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Secure Banking Login</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    body, html {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: #f5f8fb;
      height: 100%;
    }

    /* Legal notice banner */
    .legal-banner {
      background: #ffcc00;
      padding: 10px;
      text-align: center;
      font-weight: bold;
      color: #000;
      font-size: 13px;
    }

    .container {
      display: flex;
      height: calc(100% - 42px);
    }

    .left-panel {
      width: 45%;
      background: #004a8c;
      color: #fff;
      padding: 60px 40px;
    }

    .left-panel h1 {
      font-size: 32px;
      margin-bottom: 15px;
    }

    .left-panel p {
      font-size: 16px;
      line-height: 1.5;
    }

    .right-panel {
      width: 55%;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 30px;
    }

    .login-box {
      width: 100%;
      max-width: 360px;
      background: #fff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    }

    .login-box h2 {
      margin: 0 0 20px 0;
      color: #004a8c;
      text-align: center;
    }

    input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 15px;
    }

    button {
      width: 100%;
      padding: 12px;
      background: #004a8c;
      border: none;
      color: #fff;
      font-size: 16px;
      border-radius: 4px;
      cursor: pointer;
    }

    button:hover {
      background: #00376b;
    }

    .footer {
      text-align: center;
      font-size: 12px;
      color: #555;
      margin-top: 15px;
    }
  </style>
</head>

<body>

  <!-- Legal Simulation Banner -->
  <div class="legal-banner">
    
 Welcome to Bank NetBanking
  </div>

  <div class="container">
    <div class="left-panel">
      <h1>Welcome to Secure NetBanking</h1>
      <p>
        Access your account securely. 
      </p>
      <p>
        Dear Customer,
</p>
<p>
Welcome to the new login page of secure NetBanking.
Its lighter look and feel is designed to give you the best possible user experience. Please continue to login using your customer ID and password...
      </p>

<p>
First Time User?
Register Now for a host of convenient features

We have added a host of new features!
You can now do so much more:
Anywhere access through Desktop or mobile
Enhanced security measures

</p>
    </div>

    <div class="right-panel">
      <div class="login-box">
        <h2>Login to NetBanking ID</h2>

        <!-- GoPhish POST form -->
        <form method="POST" action="">
          <input type="text" name="username" placeholder="Customer ID/ User ID" required>
          <input type="password" name="password" placeholder="Password" required>
          <button type="submit">Sign In</button>
        </form>

        <div class="footer">
          © 2025 Company Secure Banking Portal — Net Banking
        </div>
      </div>
    </div>
  </div>

</body>
</html>
