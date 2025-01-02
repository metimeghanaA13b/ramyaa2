<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h2>Registration Form</h2>

    <form action="/submit" method="POST">
        <label for="first-name">First Name:</label><br>
        <input type="text" id="first-name" name="first-name" required><br><br>

        <label for="last-name">Last Name:</label><br>
        <input type="text" id="last-name" name="last-name" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br><br>

        <label for="confirm-password">Confirm Password:</label><br>
        <input type="password" id="confirm-password" name="confirm-password" required><br><br>

        <label for="gender">Gender:</label><br>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" required><br><br>

        <input type="submit" value="Register">
    </form>
</body>
</html>
