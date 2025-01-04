<h1>Cricket Player Performance Prediction</h1>
    <p>
        This project analyzes and predicts cricket player performance metrics, such as runs scored 
        and strike rates, using machine learning models like Linear Regression, Decision Tree Regressor, 
        and Random Forest Regressor. It optimizes predictions by leveraging format-specific models for 
        Test, ODI, and T20 cricket formats.
    </p>
   <h2> Features </h2>
   <ul>
     <li> Data Preprocessing </li>
       <ul>
          <li>Dataset Cleaning: Handling null values, dropping unnecessary columns, and converting date formats.</li>
          <li>Feature Engineering: Rolling averages for recent performance metrics (e.g., runs, strike rates).</li>
       </ul>
    <li>Machine Learning Models</li>
       <ul>
          <li>Linear Regression: Used as a baseline model for predictions.</li>
          <li>Decision Tree Regressor: Improved accuracy by capturing non-linear patterns.</li>
          <li>Random Forest Regressor: Delivered the most accurate predictions by combining decision trees.</li>
          <li>Cross-Validation: K-Fold cross-validation to evaluate model performance.</li>
       </ul>
    <li>Format-Specific Predictions</li>
           <ul>
               <li>Separate models were trained for Test, ODI, and T20 formats, leading to tailored and optimized predictions for each format.</li>
           </ul>
    <li>Visualization </li>
       <ul>
           <li>Performance comparison between players over the years.</li>
           <li>Actual vs. predicted runs and strike rates for models.</li>
           <li>Feature importance analysis for model insights.</li>
       </ul>
   </ul>
   <h2>Getting Started</h2>

<h3>Prerequisites</h3>
<ul>
    <li>Python 3.8+</li>
    <li>Required Libraries: <code>pandas</code>, <code>matplotlib</code>, <code>scikit-learn</code></li>
</ul>

<p>Install dependencies using:</p>
<pre><code>pip install pandas matplotlib scikit-learn</code></pre>

<h3>Usage</h3>
<ol>
    <li>Place your dataset file <code>bat.csv</code> in the project directory.</li>
    <li>Run the script:
        <pre><code>python performance_prediction.py</code></pre>
    </li>
    <li>View the visualizations and model performance metrics in the console and plots.</li>
</ol>

<hr>

<h2>Workflow</h2>

<h3>Data Preparation</h3>
<ul>
    <li>Load the dataset (<code>bat.csv</code>) using pandas.</li>
    <li>Drop unnecessary columns and handle missing values.</li>
    <li>Generate new features such as rolling averages and total performance metrics.</li>
</ul>

<h3>Model Training</h3>
<ul>
    <li>Train and evaluate models for predicting total runs and strike rates.</li>
    <li>Evaluate using metrics:
        <ul>
            <li><strong>Mean Squared Error (MSE)</strong></li>
            <li><strong>Mean Absolute Error (MAE)</strong></li>
        </ul>
    </li>
</ul>

<h3>Visualization</h3>
<ul>
    <li>Compare the yearly performance of key players like Virat Kohli, MS Dhoni, and AB de Villiers.</li>
    <li>Display graphs showing actual vs. predicted performance.</li>
</ul>
<h2>Workflow</h2>
    <h2>Model Optimization</h2>
    <p>
        The use of multiple machine learning models resulted in a progressive reduction in prediction errors:
    </p>
    <ul>
        <li><strong>Linear Regression:</strong> Baseline model for prediction.</li>
        <li>
            <strong>Decision Tree Regressor:</strong> Improved predictions with a 
            <em>74.2% reduction in MSE</em> and an <em>80.3% reduction in MAE</em>.
        </li>
        <li>
            <strong>Random Forest Regressor:</strong> Optimized predictions further with a 
            <em>90.2% reduction in MSE</em> and an <em>89.1% reduction in MAE</em>.
        </li>
    </ul>
    <h2>Format-Specific Metrics</h2>
    <p>
        Predictions were further optimized by training separate models for each cricket format, 
        resulting in significant error reductions:
    </p>
    <ul>
        <li><strong>Test Matches:</strong>
            <ul>
                <li><em>Achieved a 68.6% reduction in MSE and 78.5% reduction in MAE compared to the baseline model.</em></li>
            </ul>
        </li>
        <li><strong>ODIs:</strong>
            <ul>
                <li><em>Achieved a 98.8% reduction in MSE and 94.7% reduction in MAE compared to the baseline model.</em></li>
            </ul>
        </li>
        <li><strong>T20s:</strong>
            <ul>
                <li><em>Achieved a 99.1% reduction in MSE and 98.3% reduction in MAE compared to the baseline model.</em></li>
            </ul>
        </li>
    </ul>
Contributions and feedbacks are welcome!!
