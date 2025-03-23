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
    <title>My Website</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is the homepage.</p>
    
    <!-- External Image from Pexels -->
    <img src="https://www.pexels.com/photo/your-image-url" alt="Beautiful image from Pexels" width="600">
    
    <!-- Ordered List with Roman Numerals -->
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
    
    <!-- Table of Contacts -->
    <h2>Contact List</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>Alice Johnson</td>
            <td>123 Main St</td>
            <td>123-456-7890</td>
            <td>alice@example.com</td>
        </tr>
        <tr>
            <td>Bob Smith</td>
            <td>456 Oak St</td>
            <td>234-567-8901</td>
            <td>bob@example.com</td>
        </tr>
        <tr>
            <td>Charlie Brown</td>
            <td>789 Pine St</td>
            <td>345-678-9012</td>
            <td>charlie@example.com</td>
        </tr>
        <tr>
            <td>Diana Ross</td>
            <td>101 Maple St</td>
            <td>456-789-0123</td>
            <td>diana@example.com</td>
        </tr>
        <tr>
            <td>Edward Norton</td>
            <td>202 Birch St</td>
            <td>567-890-1234</td>
            <td>edward@example.com</td>
        </tr>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>
        
        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>
        
        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br><br>
        
        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>
        
        <!-- Dropdown Field -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
        </select>
        <br><br>
        
        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other">
        <label for="other">Other</label>
        <br><br>
        
        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="reading" name="interests" value="reading">
        <label for="reading">Reading</label>
        <br><br>
        
        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
</body>
</html>
