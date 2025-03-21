<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JAI.LOGO DESIGN</title>
    <link rel="stylesheet" href="style.css">
    <link rel="action" href="action.javascript">
</head>
<body>
    <div class="container">
        <header>
            <h1>JAI.LOGO DESIGN</h1>
            <p>Your Trusted Logo Design Service</p>
        </header>

        <section class="content">
            <h2>Contact Information</h2>
            <p>Email: <a href="mailto:jailogo@gmail.com">jailogo@gmail.com</a></p>
            <p>Phone: <a href="tel:+91380799586">6380799586</a></p>

            <h2>Website Purpose</h2>
            <p>We specialize in creating unique and professional logos tailored to your brand's identity. Let us help you build the perfect logo for your business!</p>
        </section>

        <footer>
            <button onclick="showAlert()">Request a Logo Design</button>
        </footer>
    </div>

    <script src="script.js"></script>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #007BFF; /* Blue background */
    color: white;
}

.container {
    text-align: center;
    padding: 50px;
}

/* Header Styles */
header {
    margin-bottom: 30px;
}

h1 {
    font-size: 48px;
    font-weight: bold;
}

p {
    font-size: 18px;
}

/* Contact Information Section */
.content {
    margin-top: 40px;
}

h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

a {
    color: white;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Footer Styles */
footer {
    margin-top: 40px;
}

button {
    padding: 10px 20px;
    font-size: 18px;
    background-color: white;
    color: #007BFF;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #0056b3;
    color: white;
}
// JavaScript to show an alert when the "Request a Logo Design" button is clicked
function showAlert() {
    alert("Thank you for reaching out! We will contact you shortly to discuss your logo design.");
}

