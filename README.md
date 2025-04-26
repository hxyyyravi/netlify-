# netlify-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f9fa;
      padding: 40px;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .form-container {
      background: white;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 500px;
      width: 100%;
    }
    .form-container h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }
    .form-container input, .form-container textarea {
      width: 100%;
      padding: 12px 15px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .form-container button {
      width: 100%;
      padding: 12px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    .form-container button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

<div class="form-container">
  <h2>Contact Us</h2>
  <form action="https://formsubmit.co/reddyravikumar76@email.com" method="POST">
    
    <input type="text" name="name" placeholder="Ravi kumar" required>
    <input type="email" name="email" placeholder="reddyravikumar76@email.com"required>
    <textarea name="message" placeholder="THANK YOU" rows="5" required></textarea>

    <!-- Hidden Inputs -->
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_subject" value="New Contact Form Submission!">
    <input type="hidden" name="_next" value="https://hyderabadhomesnow.netlify.app/thank-you.html">
    
    <button type="submit">Send Message</button>
  </form>
</div>

</body>
</html>
