# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Structured HTML Page</title>
    
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Image Section */
        .image-container {
            text-align: center;
            margin: 20px 0;
        }

        img {
            width: 50%;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
        }

        /* Contact Table */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background: white;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #007bff;
            color: white;
        }

        /* Form Styles */
        form {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            max-width: 500px;
            margin: 20px auto;
        }

        label {
            font-weight: bold;
        }

        input, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            background-color: #007bff;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>Introduction to HTML</li>
            <li>Basic HTML Tags</li>
            <li>Forms and Tables</li>
            <li>CSS Styling</li>
            <li>JavaScript Basics</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section class="image-container">
        <h2>Beautiful Scenery</h2>
        <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" alt="Nature Scenery from Pexels">
    </section>

    <!-- Contact Table -->
    <section>
        <h2>Contact List</h2>
        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Alice Johnson</td>
                    <td>123 Main St, NY</td>
                    <td>+1 555-1234</td>
                    <td>alice@example.com</td>
                </tr>
                <tr>
                    <td>Bob Smith</td>
                    <td>456 Elm St, CA</td>
                    <td>+1 555-5678</td>
                    <td>bob@example.com</td>
                </tr>
                <tr>
                    <td>Charlie Brown</td>
                    <td>789 Maple St, TX</td>
                    <td>+1 555-9876</td>
                    <td>charlie@example.com</td>
                </tr>
                <tr>
                    <td>Dana White</td>
                    <td>101 Pine St, FL</td>
                    <td>+1 555-6543</td>
                    <td>dana@example.com</td>
                </tr>
                <tr>
                    <td>Emma Wilson</td>
                    <td>202 Oak St, WA</td>
                    <td>+1 555-3210</td>
                    <td>emma@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <!-- Name -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>

            <!-- Email -->
            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <!-- Password -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6">

            <!-- Date -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>

            <!-- Dropdown -->
            <label for="country">Select Country:</label>
            <select id="country" name="country">
                <option value="usa">United States</option>
                <option value="uk">United Kingdom</option>
                <option value="canada">Canada</option>
                <option value="australia">Australia</option>
            </select>

            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>

            <!-- Checkboxes -->
            <label>Interests:</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>

            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label>

            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

</body>
</html>

