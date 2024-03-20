<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MTTI Student Registration</title>
</head>
<body>
    <h1>Murang'a Technical Training Institute Student Registration</h1>
    <form action="submit.php" method="post">
        <label for="firstName">First Name:</label><br>
        <input type="text" id="firstName" name="firstName" required><br>
        
        <label for="lastName">Last Name:</label><br>
        <input type="text" id="lastName" name="lastName" required><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        
        <label for="phone">Phone Number:</label><br>
        <input type="text" id="phone" name="phone" required><br>
        
        <label for="course">Select Course:</label><br>
        <select id="course" name="course" required>
            <option value="">Select Course</option>
            <option value="Computer Science">Computer Science</option>
            <option value="Electrical Engineering">Electrical Engineering</option>
            <option value="Mechanical Engineering">Mechanical Engineering</option>
            <!-- Add more options for courses -->
        </select><br>
        
        <input type="submit" value="Register">
    </form>
</body>
