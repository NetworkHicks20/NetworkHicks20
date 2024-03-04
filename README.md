<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MFA Dashboard</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>MFA Dashboard</h1>
        <div id="auth-container">
            <input type="text" id="username" placeholder="Username"><br>
            <input type="password" id="password" placeholder="Password"><br>
            <button onclick="authenticate()">Authenticate</button>
        </div>
        <div id="otp-container" style="display: none;">
            <input type="text" id="otp" placeholder="Enter OTP"><br>
            <button onclick="verifyOTP()">Verify OTP</button>
        </div>
        <p id="message"></p>
    </div>

    <script src="script.js"></script>
</body>
</html>
