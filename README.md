

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
</head>
<body>
    <form id="loginForm">
        Email: <input type="email" id="emailInput"><br>
        Password: <input type="password" id="passwordInput"><br>
        <button type="button" onclick="login()">Submit</button>
    </form>

    <script>
        function login() {
            const email = document.getElementById('emailInput').value;
            const password = document.getElementById('passwordInput').value;
            
            console.log("Email: " + email);
            console.log("Password: " + password);
        }
    </script>
</body>
</html>
```
