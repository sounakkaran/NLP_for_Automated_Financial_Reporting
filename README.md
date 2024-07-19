<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
    <h1>Financial Report Generation Project</h1>
    <h2>Introduction</h2>
    <p>This project leverages Natural Language Processing (NLP) and Generative AI to automate the generation of financial reports from transaction data. By analyzing financial transactions, the model extracts insights, generates summaries, and produces tailored financial documents.</p><br>
    <p>We collect the dataset from <a href="https://www.youdata.ai/datasets/661d0d73aa908fb615b8b2c1">YouData.ai</a>.</p><br>
     <p>Input Dataset:<a href="https://drive.google.com/file/d/1jC5ofAWIqkuZU6ie3wLgrL3mR2KK67tD/view?usp=sharing">View The Dataset</a>.</p>
    <h2>Working of the Model</h2>
    <h3>1. Data Extraction</h3>
    <p>The model starts by extracting financial data from a CSV file uploaded by the user. The CSV file should contain columns for <code>Date</code>, <code>Description</code>, <code>Amount</code>, <code>Transaction Type</code>, <code>Category</code>, and <code>Account Name</code>.</p>
    <img src="https://github.com/user-attachments/assets/ca374346-1c6f-44cc-87db-028480c7ac47" alt="Data Extraction Example" width="600">
    <h3>2. Data Processing</h3>
    <p>The extracted data is cleaned and preprocessed to ensure it is ready for analysis. This includes handling missing values, converting data types, and formatting dates.</p>
    <img src="https://github.com/user-attachments/assets/6884e9e1-de05-4407-b962-c9a1b6a8c6d7" alt="Data Processing Example" width="600">
    <h3>3. NLP Analysis</h3>
    <p>The processed data is then analyzed using NLP techniques. Sentiment analysis is performed on the transaction descriptions to understand the sentiment associated with each transaction. The model also categorizes and aggregates the data for further analysis.</p>
    <img src="https://github.com/user-attachments/assets/a2697e33-9cf1-4f48-b6ae-540d30f91ce5" alt="NLP Analysis Example" width="600">
    <h3>4. Model Training</h3>
    <p>The model is trained on historical transaction data to improve the accuracy of sentiment analysis and categorization. This involves using machine learning algorithms to learn from past data and make predictions on new data.</p>
    <img src="https://github.com/user-attachments/assets/385ea120-077d-4ca5-aeff-f2f0b7e5964b" alt="Model Training Example" width="600"><br>
    <a href="https://huggingface.co/TurkuNLP/gpt3-finnish-small">View The Model</a>
    <h3>5. Report Generation</h3>
    <p>The model generates a detailed report summarizing the financial transactions. This report includes various insights and analysis based on the transaction data.</p>
    <img src="https://github.com/user-attachments/assets/46b591c0-eddd-43d3-ac3b-921628bf707e" alt="Report Generation Exampl" width="600">
    <h3>Monthly Report Generation</h3>
    <p>In addition to the detailed report, the model generates a monthly summary report. This includes an overview of the monthly transactions, categorized spending, and trends observed during the month.</p>
    <img src="https://github.com/user-attachments/assets/0e5cc4c6-1fbd-42bd-9bc1-e7c8d0e76655" alt="Monthly Report Generation Example" width="600">
    <p>The Monthly Transaction Report:</p><br>
      <img src="https://github.com/user-attachments/assets/030adfa6-c7d1-4ea3-ad09-5f8fe4db4bba" alt="Monthly Report Generation Example" width="600"><br>
    <h2>Data Visualization</h2>
    <p>The project includes various data visualizations to enhance the understanding of the financial data:</p>
    <ul>
        <li>Monthly Total Spending: A bar chart showing the total spending for each month.</li>
        <li>Spending by Category: A bar chart visualizing the spending distribution across different categories.</li>
        <li>Sentiment Analysis: A histogram representing the sentiment scores of transaction descriptions.</li>
        <li>Scatter Plot: A scatter plot displaying the amount spent over time, categorized by the type of transaction.</li>
        <li>Pie Chart: A pie chart showing the distribution of spending by category.</li>
    </ul>
    <img src="https://github.com/user-attachments/assets/415ea065-ad0e-441c-8599-7934b3cf1f3c" alt="Monthly Total Spending" width="600">
    <img src="https://github.com/user-attachments/assets/1ac76cf1-1a6e-45db-9959-1a3d1d1e5e62" alt="Spending by Category" width="600">
    <img src="https://github.com/user-attachments/assets/2ed017ca-bdd1-4f56-9146-ec8a8d281340" alt="Sentiment Analysis" width="600">
    <img src="https://github.com/user-attachments/assets/29799223-836f-43e0-ba94-fcb6ea1ef22a" alt="Scatter Plot" width="600">
    <img src="https://github.com/user-attachments/assets/a7df4c24-eff9-40c2-a779-b8459dee901c" alt="Pie Chart" width="600">
    <h2>Usage</h2>
    <p>To use the project, follow these steps:</p>
    <ol>
        <li>Upload your transaction CSV file using the provided interface.</li>
        <li>Click the <strong>Generate Report</strong> button to analyze the data and generate the report.</li>
        <li>View the generated financial report and data visualizations.</li>
        <li>Download the monthly summary CSV file for further analysis.</li>
    </ol>
    <img src="https://github.com/user-attachments/assets/5ddf5584-1171-420c-a98c-29ce575c6092" alt="User Interface" width="600"><br>
    <a href="https://drive.google.com/file/d/1f8-ySs_a3zXZ7cvcOGgmLgMCXOzTWE6x/view?usp=sharing">View The Monthly Summary</a>.
    <h2>Generated Output</h2>
    <p>Below is an example of the generated output, which includes the detailed financial report and visualizations:</p>
    <img src="https://github.com/user-attachments/assets/83495190-6aec-4a91-a5bd-d4e4dbb0c6ec" alt="Generated Output Example" width="600">
    <h2>Conclusion</h2>
    <p>This project demonstrates how powerful NLP and Generative AI techniques can be used to automate the process of financial report generation, providing valuable insights and visualizations from raw transaction data.</p>

</body>
</html>
