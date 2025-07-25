<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Banking UI</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="card">
    <div class="balance">$0</div>
    <button class="button deposit">Deposit</button>
    <button class="button withdraw">Withdraw</button>
  </div>

</body>
</html>
--css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f2f2f2;
    font-family: Arial, sans-serif;
  }
  
  .card {
    background-color: #ffffff;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    width: 90%;
    max-width: 300px;
    text-align: center;
  }
  
  .balance {
    font-size: 28px;
    color: #2e7d32; /* green */
    margin-bottom: 25px;
  }
  
  .button {
    display: block;
    width: 100%;
    padding: 14px;
    margin: 10px 0;
    border: none;
    border-radius: 8px;
    color: white;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
  }
  
  .deposit {
    background-color: #4caf50;
  }
  
  .withdraw {
    background-color: #f44336;
  }
  
  .deposit:hover {
    background-color: #43a047;
  }
  
  .withdraw:hover {
    background-color: #e53935;
  }
  
  @media (max-width: 400px) {
    .card {
      padding: 20px;
    }
  
    .balance {
      font-size: 24px;
    }
  
    .button {
      padding: 12px;
      font-size: 15px;
    }
  }
  
