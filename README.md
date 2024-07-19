<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
    <h1>Financial Report Generation Project</h1>
    <h2>Introduction</h2>
    <p>This project leverages Natural Language Processing (NLP) and Generative AI to automate the generation of financial reports from transaction data. By analyzing financial transactions, the model extracts insights, generates summaries, and produces tailored financial documents.</p>
    <h2>Working of the Model</h2>
    <h3>1. Data Extraction</h3>
    <p>The model starts by extracting financial data from a CSV file uploaded by the user. The CSV file should contain columns for <code>Date</code>, <code>Description</code>, <code>Amount</code>, <code>Transaction Type</code>, <code>Category</code>, and <code>Account Name</code>.</p>
    <img src="./images/" alt="Data Extraction Example" width="600">
    <h3>2. NLP Analysis</h3>
    <p>The extracted data is then analyzed using NLP techniques. Sentiment analysis is performed on the transaction descriptions to understand the sentiment associated with each transaction. The model also categorizes and aggregates the data for further analysis.</p>
    <img src="nlp_analysis_example.png" alt="NLP Analysis Example" width="600">
    <h3>3. Report Generation</h3>
    <p>Using the insights obtained from the NLP analysis, the model generates a detailed financial report. The report includes a summary of the transactions, monthly spending trends, and sentiment analysis results. Additionally, the model creates a monthly summary CSV file with aggregated transaction data.</p>
    <img src="report_generation_example.png" alt="Report Generation Example" width="600">
    <h2>Data Visualization</h2>
    <p>The project includes various data visualizations to enhance the understanding of the financial data:</p>
    <ul>
        <li>Monthly Total Spending: A bar chart showing the total spending for each month.</li>
        <li>Spending by Category: A bar chart visualizing the spending distribution across different categories.</li>
        <li>Sentiment Analysis: A histogram representing the sentiment scores of transaction descriptions.</li>
        <li>Scatter Plot: A scatter plot displaying the amount spent over time, categorized by the type of transaction.</li>
        <li>Pie Chart: A pie chart showing the distribution of spending by category.</li>
    </ul>
    <img src="monthly_total_spending.png" alt="Monthly Total Spending" width="600">
    <img src="spending_by_category.png" alt="Spending by Category" width="600">
    <img src="sentiment_analysis.png" alt="Sentiment Analysis" width="600">
    <img src="scatter_plot.png" alt="Scatter Plot" width="600">
    <img src="pie_chart.png" alt="Pie Chart" width="600">
    <h2>Usage</h2>
    <p>To use the project, follow these steps:</p>
    <ol>
        <li>Upload your transaction CSV file using the provided interface.</li>
        <li>Click the <strong>Generate Report</strong> button to analyze the data and generate the report.</li>
        <li>View the generated financial report and data visualizations.</li>
        <li>Download the monthly summary CSV file for further analysis.</li>
    </ol>
    <img src="user_interface.png" alt="User Interface" width="600">
    <h2>Conclusion</h2>
    <p>This project demonstrates how powerful NLP and Generative AI techniques can be used to automate the process of financial report generation, providing valuable insights and visualizations from raw transaction data.</p>

</body>
</html>
