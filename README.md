<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Data Handling</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="script.js"> 
</head>
<body>

    <h1>User Registration Form</h1>
    <form id="registrationForm">
        <label for="name">Name:</label>
        <input type="text" id="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" required>
        
        <label for="contactMethod">Preferred Contact Method:</label>
        <select id="contactMethod" required>
            <option value="">Select...</option>
            <option value="email">Email</option>
            <option value="phone">Phone</option>
        </select>
        
        <label>
            <input type="checkbox" id="terms" required> I accept terms and conditions
        </label>
        
        <button type="submit">Submit</button>
    </form>

    <div id="formSummary"></div>

    <script src="script.js"></script>
</body>
</html>
