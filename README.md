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
    <title>Contacts and Registration Form</title>
</head>

<body>
    <header>
        <h1>Contacts and Registration</h1>
    </header>

    <section>
        <h2>Important Points</h2>
        <ol type="I">
            <li>Introduction</li>
            <li>Contact Information</li>
            <li>Registration Form</li>
        </ol>
    </section>

    <section>
        <h2>Our Visual Inspiration</h2>
        <img src="https://images.pexels.com/photos/1658418/pexels-photo-1658418.jpeg" alt="Inspiration" style="width: 100%; height: auto;">
    </section>

    <section>
        <h2>Contact List</h2>
        <table border="1">
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
                    <td>John Doe</td>
                    <td>123 Kenyatta Avenue, Nairobi, Kenya</td>
                    <td>(070) 123-4567</td>
                    <td>johndoe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Moi Avenue, Mombasa, Kenya</td>
                    <td>(071) 234-5678</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Emily Johnson</td>
                    <td>789 Ngong Road, Nairobi, Kenya</td>
                    <td>(072) 345-6789</td>
                    <td>emilyj@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>101 Kenyatta Road, Kisumu, Kenya</td>
                    <td>(073) 456-7890</td>
                    <td>michaelb@example.com</td>
                </tr>
                <tr>
                    <td>Sarah Lee</td>
                    <td>202 Thika Road, Nairobi, Kenya</td>
                    <td>(074) 567-8901</td>
                    <td>sarahlee@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Register Here</h2>
        <form action="#" method="POST">
            <fieldset>
                <legend>Personal Information</legend>
                
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" placeholder="John Doe" required>
                <br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" value="dee@mail.com" required>
                <br>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter your password" required>
                <br>

                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required>
                <br>

                <label for="gender">Gender:</label>
                <select id="gender" name="gender" required>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>
                <br>

                <label>Preferred Contact Method:</label>
                <input type="radio" id="email_contact" name="contact_method" value="email" required>
                <label for="email_contact">Email</label>
                <input type="radio" id="phone_contact" name="contact_method" value="phone" required>
                <label for="phone_contact">Phone</label>
                <br>

                <label>Interests:</label>
                <input type="checkbox" id="newsletter" name="interests" value="newsletter">
                <label for="newsletter">Subscribe to newsletter</label>
                <input type="checkbox" id="offers" name="interests" value="offers">
                <label for="offers">Receive special offers</label>
                <br>

                <button type="submit">Register</button>
            </fieldset>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Your Company. All Rights Reserved.</p>
    </footer>

</body>

</html>
