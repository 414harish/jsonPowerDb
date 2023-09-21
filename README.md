# jsonPowerDb
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Employee Form using the JPDB API</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            
        }

        .container {
            max-width: 500px;
            margin: 0 auto;
            padding: 20px;
           
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }

        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
        }

        .form-group button {
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
            padding: 10px 20px;
            cursor: pointer;
        }

        .form-group button[type="reset"] {
            background-color: #007bff;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Employee Form using the JPDB API</h2>
        <form id="employee-form">
            <div class="form-group">
                <label for="employee-id">Employee ID:</label>
                <input type="text" id="employee-id" name="employee-id" required>
            </div>
            <div class="form-group">
                <label for="employee-name">Employee Name:</label>
                <input type="text" id="employee-name" name="employee-name" required>
            </div>
            <div class="form-group">
                <label for="basic-salary">Basic Salary:</label>
                <input type="number" id="basic-salary" name="basic-salary" required>
            </div>
            <div class="form-group">
                <label for="hra">HRA:</label>
                <input type="number" id="hra" name="hra">
            </div>
            <div class="form-group">
                <label for="da">DA:</label>
                <input type="number" id="da" name="da">
            </div>
            <div class="form-group">
                <label for="deduction">Deduction:</label>
                <input type="number" id="deduction" name="deduction">
            </div>
            <div class="form-group">
                <button type="submit">Submit</button>
                <button type="Continue">Continue</button>
                <button type="reset">Reset</button>
            </div>
        </form>
    </div>
