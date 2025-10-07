<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Employee Directory Search</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f6fa;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #2e86de;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .container {
      max-width: 900px;
      margin: 30px auto;
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .search-box {
      text-align: center;
      margin-bottom: 20px;
    }

    .search-box input {
      width: 80%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    table th, table td {
      padding: 12px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }

    table th {
      background-color: #2e86de;
      color: white;
    }

    tr:hover {
      background-color: #f1f1f1;
    }

    footer {
      text-align: center;
      padding: 15px;
      color: #777;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Employee Directory Search</h1>
  </header>

  <div class="container">
    <div class="search-box">
      <input type="text" placeholder="Search employee by name, department, or ID...">
    </div>

    <table>
      <thead>
        <tr>
          <th>Employee ID</th>
          <th>Name</th>
          <th>Department</th>
          <th>Email</th>
          <th>Phone</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>EMP001</td>
          <td>John Doe</td>
          <td>IT</td>
          <td>john.doe@example.com</td>
          <td>9876543210</td>
        </tr>
        <tr>
          <td>EMP002</td>
          <td>Mary Smith</td>
          <td>HR</td>
          <td>mary.smith@example.com</td>
          <td>9876501234</td>
        </tr>
        <tr>
          <td>EMP003</td>
          <td>Ravi Kumar</td>
          <td>Finance</td>
          <td>ravi.kumar@example.com</td>
          <td>9988776655</td>
        </tr>
        <tr>
          <td>EMP004</td>
          <td>Sneha Patel</td>
          <td>Marketing</td>
          <td>sneha.patel@example.com</td>
          <td>9876123456</td>
        </tr>
      </tbody>
    </table>
  </div>

  <footer>
    © 2025 Employee Directory | All Rights Reserved
  </footer>

</body>
</html>
