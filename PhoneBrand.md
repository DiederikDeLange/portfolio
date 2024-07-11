<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embedded Power BI Report</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        h1 {
            text-align: center;
            padding: 20px;
        }
        iframe {
            width: 100%;
            height: 80vh;
            border: none;
        }
        .content {
            padding: 10px;
            text-align: center;
        }
        a {
            display: inline-block;
            margin-top: 20px;
            text-decoration: none;
            color: #007BFF;
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <h1>My Power BI Report</h1>
    <iframe
        src="https://app.powerbi.com/reportEmbed?reportId=db6d4b82-a12c-483b-b732-8b1bb362ee63&autoAuth=true&ctid=aaee71f7-315f-4714-bad5-8951c8414782"
        allowFullScreen="true"
    ></iframe>
    <div class="content">
        <p>Welcome to the new page.</p>
        <p>This is the content of the new page.</p>
        <a href="README.md">Back to the main page</a>
    </div>
</body>
</html>
