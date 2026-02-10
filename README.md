# House-Sale-Prediction
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>House Price Prediction Project</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f5f7fa;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 1000px;
            margin: auto;
            background: #ffffff;
            padding: 30px;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 4px solid #3498db;
            padding-bottom: 10px;
        }
        h2 {
            color: #2c3e50;
            border-left: 5px solid #3498db;
            padding-left: 10px;
            margin-top: 40px;
        }
        h3 {
            color: #34495e;
        }
        ul {
            margin-left: 20px;
        }
        code, pre {
            background: #eef2f5;
            padding: 10px;
            border-radius: 6px;
            display: block;
            overflow-x: auto;
        }
        .badge {
            display: inline-block;
            background: #3498db;
            color: #fff;
            padding: 6px 12px;
            border-radius: 5px;
            font-size: 13px;
            margin-right: 5px;
        }
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 14px;
            color: #777;
        }
    </style>
</head>
<body>

<div class="container">

<h1>🏠 House Price Prediction Project</h1>
<span class="badge">Machine Learning</span>
<span class="badge">Flask</span>
<span class="badge">Python</span>
<span class="badge">Render</span>

<h2>📑 Table of Contents</h2>
<ul>
    <li>Acknowledgements</li>
    <li>Project Overview</li>
    <li>Dataset Description</li>
    <li>Technology Stack</li>
    <li>Implementation Steps</li>
    <li>Code Explanation</li>
    <li>Model Development</li>
    <li>Deployment Process</li>
    <li>Results and Output</li>
    <li>Challenges and Solutions</li>
    <li>Future Enhancements</li>
    <li>Conclusion</li>
    <li>References</li>
</ul>

<h2>1. 🙏 Acknowledgements</h2>
<h3>Dataset Source</h3>
<ul>
    <li><strong>Dataset:</strong> House Sales in King County, USA</li>
    <li><strong>Source:</strong> Kaggle</li>
    <li><strong>Contributor:</strong> Shreya Chaudhary</li>
</ul>

<h3>Tools & Libraries</h3>
<ul>
    <li>Flask</li>
    <li>Scikit-learn</li>
    <li>NumPy</li>
    <li>Pandas</li>
    <li>Pickle</li>
    <li>HTML & CSS</li>
    <li>Render</li>
    <li>Git & GitHub</li>
</ul>

<h2>2. 📌 Project Overview</h2>
<p>
This project is a machine learning web application that predicts house prices
based on features such as size, location, condition, and time-related factors.
</p>

<h3>Key Features</h3>
<ul>
    <li>User-friendly interface</li>
    <li>Real-time house price prediction</li>
    <li>17 input features</li>
    <li>Deployed web application</li>
</ul>

<h2>3. 📊 Dataset Description</h2>
<ul>
    <li><strong>Total Records:</strong> 21,613</li>
    <li><strong>Features:</strong> 18</li>
    <li><strong>Location:</strong> King County, Washington, USA</li>
    <li><strong>Time Period:</strong> May 2014 – May 2015</li>
</ul>

<h2>4. 🛠 Technology Stack</h2>
<h3>Backend</h3>
<ul>
    <li>Python</li>
    <li>Flask</li>
    <li>Scikit-learn</li>
    <li>Pandas & NumPy</li>
</ul>

<h3>Frontend</h3>
<ul>
    <li>HTML5</li>
    <li>CSS3</li>
</ul>

<h2>5. 📂 Project Structure</h2>
<pre>
House-Price-Prediction/
│
├── app.py
├── MINI_PROJECT.pkl
├── requirements.txt
├── Procfile
├── templates/
├── static/
└── README.html
</pre>

<h2>6. ⚙️ Implementation Steps</h2>
<pre>
python -m venv venv
venv\Scripts\activate
pip install flask numpy pandas scikit-learn gunicorn
python app.py
</pre>

<h2>7. 🧠 Model Development</h2>
<ul>
    <li>Algorithm: Linear Regression</li>
    <li>Metrics: RMSE, R² Score</li>
    <li>Custom implementation using SVD</li>
</ul>

<h2>8. 🚀 Deployment Process</h2>
<ul>
    <li>GitHub repository hosting</li>
    <li>Render cloud deployment</li>
    <li>Gunicorn production server</li>
</ul>

<h2>9. 📈 Results and Output</h2>
<ul>
    <li>Prediction response time: &lt; 2 seconds</li>
    <li>24/7 availability</li>
    <li>Accurate price estimation</li>
</ul>

<h2>10. ⚠️ Challenges and Solutions</h2>
<ul>
    <li>Feature encoding → Label encoding</li>
    <li>Model persistence → Pickle</li>
    <li>Deployment errors → Correct dependencies</li>
</ul>

<h2>11. 🔮 Future Enhancements</h2>
<ul>
    <li>Advanced ML models</li>
    <li>Data visualization</li>
    <li>Prediction history & export</li>
</ul>

<h2>12. ✅ Conclusion</h2>
<p>
This project demonstrates a complete end-to-end machine learning pipeline,
from data preprocessing to real-world deployment.
</p>

<h2>13. 📚 References</h2>
<ul>
    <li>Flask Documentation</li>
    <li>Scikit-learn Documentation</li>
    <li>Render Documentation</li>
</ul>

<footer>
    <p><strong>Project By:</strong> Architha Sagi</p>
    <p>Last Updated: 10-02-2026</p>
</footer>

</div>

</body>
</html>

