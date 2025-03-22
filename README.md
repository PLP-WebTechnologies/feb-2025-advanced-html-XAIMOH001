<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
</head>
<body>
    <h1>Advanced HTML5 Elements</h1>

    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Python</li>
        <li>Django</li>
    </ol>

    <!-- External Image -->
    <h2>Image from Pexels</h2>
    <img src="images/image copy 3.png" alt="Sample Image from Pexels" width="500">

    <!-- Contacts Table -->
    <h2>Contacts Table</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Wanjiku Mwangi</td>
            <td>123 Moi Avenue, Nairobi</td>
            <td>+254712345678</td>
            <td>wanjiku@example.com</td>
        </tr>
        <tr>
            <td>Otieno Odhiambo</td>
            <td>456 Kenyatta Road, Kisumu</td>
            <td>+254798765432</td>
            <td>otieno@example.com</td>
        </tr>
        <tr>
            <td>Kamau Njoroge</td>
            <td>789 Kimathi Street, Nakuru</td>
            <td>+254711222333</td>
            <td>kamau@example.com</td>
        </tr>
        <tr>
            <td>Achieng' Atieno</td>
            <td>321 Uhuru Highway, Mombasa</td>
            <td>+254744555666</td>
            <td>achieng@example.com</td>
        </tr>
        <tr>
            <td>Mutua Musyoka</td>
            <td>987 Machakos Town</td>
            <td>+254777888999</td>
            <td>mutua@example.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter password" required minlength="6"><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="Other">
        <label for="other">Other</label><br><br>

        <label for="course">Select Course:</label>
        <select id="course" name="course" required>
            <option value="">--Select--</option>
            <option value="web">Web Development</option>
            <option value="data">Data Science</option>
            <option value="ai">Artificial Intelligence</option>
        </select><br><br>

        <label>Interests:</label><br>
        <input type="checkbox" id="coding" name="interest" value="Coding">
        <label for="coding">Coding</label>
        <input type="checkbox" id="gaming" name="interest" value="Gaming">
        <label for="gaming">Gaming</label>
        <input type="checkbox" id="reading" name="interest" value="Reading">
        <label for="reading">Reading</label><br><br>

        <button type="submit">Register</button>
    </form>

</body>
</html>
