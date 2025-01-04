<h1>Cricket Player Performance Prediction</h1>
    <p>
        This project analyzes and predicts cricket player performance metrics, such as runs scored 
        and strike rates, using machine learning models like Linear Regression, Decision Tree Regressor, 
        and Random Forest Regressor. It optimizes predictions by leveraging format-specific models for 
        Test, ODI, and T20 cricket formats.
    </p>

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