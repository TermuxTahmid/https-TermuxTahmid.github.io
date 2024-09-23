FOUNDER BY NAJMIN AKTER NODI
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bangladesh Blood Service Center Mymensingh - A blood donation organization.">
    <title>Bangladesh Blood Service Center Mymensingh</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #e74c3c;
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            margin-bottom: 10px;
        }
        header img {
            width: 150px;
            height: auto;
        }
        nav {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        nav a {
            margin: 0 15px;
            padding: 10px 20px;
            background-color: #2c3e50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
        }
        nav a:hover {
            background-color: #34495e;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        section h2 {
            margin-bottom: 15px;
            font-size: 24px;
        }
        section p {
            margin-bottom: 20px;
            font-size: 18px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
        .form-section {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            max-width: 500px;
            margin: 0 auto;
        }
        .form-section form {
            display: flex;
            flex-direction: column;
        }
        .form-section input[type="text"], 
        .form-section input[type="email"], 
        .form-section textarea {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .form-section input[type="submit"] {
            padding: 10px;
            background-color: #e74c3c;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .form-section input[type="submit"]:hover {
            background-color: #c0392b;
        }
        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 25px;
            background-color: #27ae60;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .button:hover {
            background-color: #2ecc71;
        }
        .donate-buttons {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .donate-buttons a {
            display: inline-block;
            margin: 0 10px;
            padding: 10px 20px;
            background-color: #2980b9;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .donate-buttons a:hover {
            background-color: #3498db;
        }

        @media screen and (max-width: 768px) {
            nav {
                flex-direction: column;
            }
            nav a {
                margin-bottom: 10px;
                font-size: 14px;
            }
            .form-section {
                width: 90%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Bangladesh Blood Service Center Mymensingh</h1>
    <img src="https://ibb.co.com/GMwTXZz" alt="Organization Logo">
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
    <p>We are dedicated to saving lives by organizing blood donation drives and providing blood to those in need.</p>
</section>

<section id="live-updates">
    <h2>Live Updates</h2>
    <p>Stay updated with the latest news about blood donation events and emergency needs.</p>
    <a href="https://your-live-update-link.com" class="button">Check Live Updates</a>
</section>

<section id="donate">
    <h2>Donate Blood</h2>
    <p>If you are interested in donating blood or checking the donor list, please click on the button below.</p>
    <div class="donate-buttons">
        <a href="#donor-list">Donor List</a>
        <a href="#submit-info">Submit Your Info</a>
    </div>
</section>

<section id="donor-list">
    <h2>Donor List</h2>
    <p>Here you can see the list of available blood donors. (You can integrate a dynamic donor list)</p>
</section>

<section id="submit-info" class="form-section">
    <h2>Submit Your Information</h2>
    <form action="https://formsubmit.co/your-email@example.com" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="text" name="blood_group" placeholder="Your Blood Group" required>
        <textarea name="message" rows="4" placeholder="Additional Details" required></textarea>
        <a href="https://wa.me/8801XXXXXXXXX" target="_blank" class="button">WhatsApp Us</a>
        <input type="submit" value="Submit Information">
        <input type="hidden" name="_next" value="https://thank-you-page.com">
        <input type="hidden" name="_subject" value="New Donor Submission">
    </form>
</section>

<section id="contact" class="form-section">
    <h2>Contact Us</h2>
    <form action="https://formsubmit.co/your-email@example.com" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
        <a href="https://wa.me/8801XXXXXXXXX" target="_blank" class="button">WhatsApp Us</a>
        <input type="submit" value="Send Message">
        <input type="hidden" name="_next" value="https://thank-you-page.com">
        <input type="hidden" name="_subject" value="New Contact Form Submission">
    </form>
</section>

<footer>
    <p>Bangladesh Blood Service Center Mymensingh &copy; 2024</p>
</footer>

</body>
</html>
