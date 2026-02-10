# House-Sale-Prediction
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>House Price Prediction</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f4f6f8;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #ffffff;
            padding: 30px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            border-bottom: 3px solid #3498db;
            padding-bottom: 10px;
        }
        ul {
            margin-left: 20px;
        }
        code {
            background: #eef1f5;
            padding: 3px 6px;
            border-radius: 4px;
        }
        .badge {
            display: inline-block;
            background: #3498db;
            color: #fff;
            padding: 5px 10px;
            border-radius: 4px;
            font-size: 12px;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 14px;
            color: #777;
        }
    </style>
</head>
<body>

<div class="container">

    <h1>🏠 House Price Prediction</h1>
    <span class="badge">Machine Learning</span>
    <span class="badge">Flask</span>
    <span class="badge">Python</span>

    <h2>📌 Project Overview</h2>
    <p>
        This project is a machine learning web application that predicts house prices
        based on various input features such as size, location, condition, and date.
        The model is trained on real housing data and deployed using Flask.
    </p>

    <h2>🎯 Objectives</h2>
    <ul>
        <li>Build a regression model for house price prediction</li>
        <li>Create a user-friendly web interface</li>
        <li>Deploy the application online</li>
    </ul>

    <h2>📊 Dataset</h2>
    <ul>
        <li><strong>Name:</strong> House Sales in King County, USA</li>
        <li><strong>Source:</strong> Kaggle</li>
        <li><strong>Records:</strong> 21,613</li>
    </ul>

    <h2>🛠️ Technology Stack</h2>
    <ul>
        <li>Python</li>
        <li>Flask</li>
        <li>Scikit-learn</li>
        <li>Pandas & NumPy</li>
        <li>HTML & CSS</li>
    </ul>

    <h2>📂 Project Structure</h2>
    <pre>
House-Price-Prediction/
│
├── app.py
├── model.pkl
├── requirements.txt
├── Procfile
├── templates/
├── static/
└── README.html
    </pre>

    <h2>🚀 How to Run</h2>
    <ol>
        <li>Install dependencies</li>
        <code>pip install -r requirements.txt</code>
        <li>Run the Flask app</li>
        <code>python app.py</code>
        <li>Open browser and go to</li>
        <code>http://localhost:5000</code>
    </ol>

    <h2>📈 Output</h2>
    <p>
        The application takes user input and displays the predicted house price instantly.
    </p>

    <h2>🔮 Future Enhancements</h2>
    <ul>
        <li>Use advanced ML models</li>
        <li>Add data visualizations</li>
        <li>Improve UI and responsiveness</li>
    </ul>

    <h2>👩‍💻 Author</h2>
    <p>
        <strong>Architha Sagi</strong><br>
        Mini Project – House Price Prediction
    </p>

    <footer>
        <p>© 2026 House Price Prediction Project</p>
    </footer>

</div>

</body>
</html>
