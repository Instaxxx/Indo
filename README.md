
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GoIndex Template</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .file-list {
            list-style: none;
            padding: 0;
        }

        .file-list li {
            display: flex;
            justify-content: space-between;
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }

        .file-list li:last-child {
            border-bottom: none;
        }

        .file-list a {
            text-decoration: none;
            color: #4CAF50;
        }

        .file-list a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>My GoIndex</h1>
    </header>

    <div class="container">
        <h2>File List</h2>
        <ul class="file-list">
            <li>
                <a href="#">File 1.txt</a>
                <span>10 KB</span>
            </li>
            <li>
                <a href="#">File 2.jpg</a>
                <span>2 MB</span>
            </li>
            <li>
                <a href="#">File 3.pdf</a>
                <span>500 KB</span>
            </li>
        </ul>
    </div>

    <footer>
        &copy; 2024 My GoIndex Template
    </footer>
</body>
</html>
