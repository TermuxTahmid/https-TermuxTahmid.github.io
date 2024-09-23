<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bangladesh Blood Service Center Mymensingh - A blood donation organization.">
    <title>Bangladesh Blood Service Center Mymensingh</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #e74c3c;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        nav {
            margin: 10px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            padding: 10px 15px;
            background-color: #2c3e50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        nav a:hover {
            background-color: #34495e;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        form {
            margin: 20px auto;
            width: 50%;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        input[type="text"], input[type="email"], textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #e74c3c;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
        }
        input[type="submit"]:hover {
            background-color: #c0392b;
        }
        img {
            width: 150px;
            height: auto;
            margin-top: 10px;
        }
        .button {
            display: block;
            background-color: #27ae60;
            color: white;
            padding: 15px;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #2ecc71;
        }
        .donate-buttons {
            margin: 20px auto;
            text-align: center;
        }
        .donate-buttons a {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            background-color: #2980b9;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .donate-buttons a:hover {
            background-color: #3498db;
        }
    </style>
</head>
<body>

<header>
    <h1>Bangladesh Blood Service Center Mymensingh</h1>
    <img src="path-to-your-logo/logo.jpg" alt="Organization Logo">
    <nav>
        <a href="#home">Home</a>
        <a href="#live-updates">Live Update</a>
        <a href="tel:+8801XXXXXXXXX">Call Us</a>
        <a href="#contact">Contact</a>
        <a href="#donate">Donate</a>
    </nav>
</header>

<section id="home">
    <h2>Welcome to Bangladesh Blood Service Center Mymensingh</h2>
    <p>We are a blood donation organization dedicated to saving lives. Join us in our mission to provide life-saving blood to those in need.</p>
</section>

<section id="live-updates">
    <h2>Live Updates</h2>
    <p>Stay updated with the latest blood donation drives and emergency blood needs in your area.</p>
    <a href="https://your-live-update-link.com" class="button">Check Live Updates</a>
</section>

<section id="donate">
    <h2>Donate Blood</h2>
    <p>If you are interested in donating blood, please click on the button below to see the list of donors or to submit your information.</p>
    <div class="donate-buttons">
        <a href="#donor-list">Donor List</a>
        <a href="#submit-info">Submit Your Info</a>
    </div>
</section>

<section id="donor-list">
    <h2>Donor List</h2>
    <p>List of available donors will be displayed here. (You can integrate a dynamic donor list system)</p>
</section>

<section id="submit-info">
    <h2>Submit Your Information</h2>
    <form action="https://formsubmit.co/your-email@example.com" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="text" name="blood_group" placeholder="Your Blood Group" required>
        <textarea name="message" rows="5" placeholder="Your Message (e.g., available donation time)" required></textarea>
        
        <!-- WhatsApp link -->
        <a href="https://wa.me/8801XXXXXXXXX" target="_blank" style="display:block; margin: 10px 0; color: #25D366; text-decoration: none;">Contact us via WhatsApp</a>
        
        <input type="submit" value="Submit Information">
        
        <!-- Hidden field to redirect form to your email -->
        <input type="hidden" name="_next" value="https://your-thank-you-page.com">
        <input type="hidden" name="_subject" value="New Donor Submission!">
    </form>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <form action="https://formsubmit.co/your-email@example.com" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        
        <!-- WhatsApp link -->
        <a href="https://wa.me/8801XXXXXXXXX" target="_blank" style="display:block; margin: 10px 0; color: #25D366; text-decoration: none;">Contact us via WhatsApp</a>
        
        <input type="submit" value="Send Message">
        
        <!-- Hidden field to redirect form to your email -->
        <input type="hidden" name="_next" value="https://your-thank-you-page.com">
        <input type="hidden" name="_subject" value="New Contact Form Submission!">
    </form>
</section>

<footer>
    <p>Bangladesh Blood Service Center Mymensingh &copy; 2024</p>
</footer>

</body>
</html>
