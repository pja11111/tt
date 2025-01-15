<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Card Example</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
     
      margin: 0;
      background-color: #ffffff8e;
    }

    .card {
      width: 200px;
      border: 1px solid #4caf50;
      border-radius: 8px;
      text-align: center;
      font-size: 16px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    .card-header {
      background-color: #4caf50;
      color: white;
      padding: 10px;
      font-weight: bold;
      border-radius: 8px 8px 0 0;
    }

    .card-body {
      padding: 15px;
      font-size: 18px;
      font-weight: bold;
      
      color: #333;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="card-header">
      Pool Hashrate
    </div>
    <div class="card-body">
      376.1 Gh/s
    </div>
  </div>
</body>
</html>
