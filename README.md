# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Payment Received</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    .container {
      margin: 40px auto;
      padding: 20px;
      max-width: 400px;
      background: #ffffff;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    h1 {
      color: #28a745;
    }
    .qr {
      width: 200px;
      height: 200px;
      margin: 20px auto;
    }
    .upi-id {
      margin-top: 10px;
      font-size: 16px;
      color: #555;
    }
    .pay-btn {
      display: inline-block;
      margin-top: 20px;
      background: #007bff;
      color: #fff;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 6px;
      font-size: 16px;
    }
    .pay-btn:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Pay Now – Your Penalty Recovery Tax</h1>
    <img src="your-qr-code.png" alt="Scan to Pay" class="qr" />
    <div class="upi-id">UPI ID: yourupi@bank</div>
    <a class="pay-btn" href="upi://pay?pa=yourupi@bank&pn=Your+Name&cu=INR">Pay Now</a>
  </div>
</body>
</html>
