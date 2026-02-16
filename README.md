# MINI_PROJECT_1


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>House Price Prediction Project</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            background-color: #f4f6f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #1f4e79;
        }
        .section {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        ul {
            margin-left: 20px;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>House Price Prediction Project</h1>

    <div class="section">
        <h2>1. Project Overview</h2>
        <p>
            This project is a Machine Learning web application that predicts house prices 
            based on various features such as location, size, condition, and date of sale.
        </p>
        <ul>
            <li>Real-time price prediction</li>
            <li>17 input features</li>
            <li>Deployed using Flask and Render</li>
            <li>User-friendly web interface</li>
        </ul>
    </div>

    <div class="section">
        <h2>2. Dataset Description</h2>
        <ul>
            <li>Total Records: 21,613</li>
            <li>Features: 18 columns</li>
            <li>Location: King County, Washington, USA</li>
            <li>Time Period: May 2014 – May 2015</li>
        </ul>
    </div>

    <div class="section">
        <h2>3. Technology Stack</h2>
        <h3>Backend</h3>
        <ul>
            <li>Python</li>
            <li>Flask</li>
            <li>Scikit-learn</li>
            <li>Pandas</li>
            <li>NumPy</li>
            <li>Pickle</li>
        </ul>

        <h3>Frontend</h3>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
        </ul>

        <h3>Deployment</h3>
        <ul>
            <li>Render</li>
            <li>GitHub</li>
        </ul>
    </div>

    <div class="section">
        <h2>4. Implementation Steps</h2>
        <ol>
            <li>Data preprocessing and feature engineering</li>
            <li>Train Linear Regression model</li>
            <li>Save model using pickle (.pkl)</li>
            <li>Develop Flask web application</li>
            <li>Deploy on Render</li>
        </ol>
    </div>

    <div class="section">
        <h2>5. Model Development</h2>
        <p>
            Linear Regression model was implemented using custom SVD-based approach.
        </p>
        <ul>
            <li>RMSE – Root Mean Squared Error</li>
            <li>R² Score – Model accuracy</li>
        </ul>
    </div>

    <div class="section">
        <h2>6. Features Used for Prediction</h2>
        <ul>
            <li>Bedrooms</li>
            <li>Bathrooms</li>
            <li>Sqft Living</li>
            <li>Sqft Lot</li>
            <li>Floors</li>
            <li>Waterfront</li>
            <li>View</li>
            <li>Condition</li>
            <li>Sqft Above</li>
            <li>Sqft Basement</li>
            <li>Year Built</li>
            <li>Year Renovated</li>
            <li>City (Encoded)</li>
            <li>Country (Encoded)</li>
            <li>Year</li>
            <li>Month</li>
            <li>Day</li>
        </ul>
    </div>

    <div class="section">
        <h2>7. Challenges & Solutions</h2>
        <ul>
            <li>Encoded categorical variables manually</li>
            <li>Used pickle for model serialization</li>
            <li>Converted form input strings to float</li>
            <li>Fixed deployment dependency issues</li>
        </ul>
    </div>

    <div class="section">
        <h2>8. Future Enhancements</h2>
        <ul>
            <li>Random Forest / Gradient Boosting</li>
            <li>Hyperparameter tuning</li>
            <li>Data visualization dashboard</li>
            <li>Database integration</li>
        </ul>
    </div>

    <div class="section">
        <h2>9. Conclusion</h2>
        <p>
            This project demonstrates a complete end-to-end Machine Learning pipeline,
            from data preprocessing to deployment of a live web application.
        </p>
    </div>

    <footer>
        Project By: M. Sohail <br>
        Last Updated: 11-02-2026 <br>
        Live App: <a href="https://mini-project-1-1-d3bl.onrender.com/" target="_blank">
            House Price Predictor
        </a>
    </footer>

</body>
</html>


