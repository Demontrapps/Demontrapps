<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RiskyBets.gg - Play & Win!</title>
    <style>
        body {
            font-family: 'Trebuchet MS', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #ffffff;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #ff4d4d;
        }
        header .logo {
            font-size: 28px;
            font-weight: bold;
            color: #ffffff;
        }
        header nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #ffffff;
            font-weight: bold;
        }
        header nav a:hover {
            color: #ffcc99;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://via.placeholder.com/1200x400/ff4d4d/ffffff?text=RiskyBets.gg') no-repeat center/cover;
            color: #ffffff;
        }
        .hero h1 {
            font-size: 48px;
            margin: 0;
        }
        .hero p {
            font-size: 20px;
            margin: 15px 0 30px;
        }
        .hero a {
            text-decoration: none;
            padding: 15px 30px;
            background-color: #4da6ff;
            color: #ffffff;
            font-weight: bold;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #ff4d4d;
            color: #ffffff;
        }
        footer a {
            color: #ffcc99;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">RiskyBets.gg</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="login.html">Login</a>
            <a href="signup.html">Create Account</a>
        </nav>
    </header>
    <section class="hero">
        <h1>Welcome to RiskyBets.gg</h1>
        <p>The ultimate destination for thrilling bets and big rewards!</p>
        <a href="signup.html">Join Now</a>
    </section>
    <footer>
        <p>&copy; 2024 RiskyBets.gg. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - RiskyBets.gg</title>
    <style>
        body {
            font-family: 'Trebuchet MS', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: #333333;
            padding: 40px;
            border-radius: 10px;
            width: 100%;
            max-width: 400px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
            color: #ff4d4d;
        }
        form label {
            display: block;
            margin-bottom: 5px;
        }
        form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
        }
        form button {
            width: 100%;
            padding: 10px;
            background-color: #ff4d4d;
            color: #ffffff;
            border: none;
            border-radius: 5px;
            font-weight: bold;
        }
        form button:hover {
            background-color: #e63939;
        }
        .links {
            text-align: center;
            margin-top: 15px;
        }
        .links a {
            color: #4da6ff;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Login</h1>
        <form action="#">
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>
        <div class="links">
            <p>Don't have an account? <a href="signup.html">Create one</a></p>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up - RiskyBets.gg</title>
    <style>
        body {
            font-family: 'Trebuchet MS', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #ffffff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: #333333;
            padding: 40px;
            border-radius: 10px;
            width: 100%;
            max-width: 400px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
            color: #ff4d4d;
        }
        form label {
            display: block;
            margin-bottom: 5px;
        }
        form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
        }
        form button {
            width: 100%;
            padding: 10px;
            background-color: #ff4d4d;
            color: #ffffff;
            border: none;
            border-radius: 5px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Create Account</h1>
        <form action="#">
            <label for="username">Username</label>
            <input type="text" id="username" name="username" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Sign Up</button>
        </form>
    </div>
</body>
</html>
