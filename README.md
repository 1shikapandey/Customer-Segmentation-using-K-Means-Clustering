<!DOCTYPE html>
<html lang="en">
<body>

<h1>Customer Segmentation using K-Means Clustering</h1>

<p>
This project applies K-Means clustering to analyze customer datasets and uncover hidden patterns in purchasing behaviour and demographic attributes. By grouping similar customers into meaningful segments, the model enables businesses to better understand their audience, personalize marketing strategies, and improve decision-making through data-driven insights.
</p>

<h2>Prerequisites</h2>
<ul>
  <li>Python (3.8+)</li>
  <li>scikit-learn</li>
  <li>pandas</li>
  <li>numpy</li>
  <li>matplotlib</li>
</ul>

<h2>Dataset</h2>
<p>
This project uses a customer dataset containing features such as Annual Income, Spending Score, Age, and Gender.
You can replace the sample dataset with your own customer data (in CSV format) by keeping the column names consistent.
</p>

<h2>🚀 Installation</h2>
<pre>
git clone https://github.com/1shikapandey/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
pip install -r requirements.txt
</pre>

<h2>⚙️ Usage</h2>
<pre>
python main.py
</pre>
<ul>
  <li>The script loads the dataset.</li>
  <li>Performs basic data preprocessing.</li>
  <li>Applies the K-Means algorithm to cluster customers.</li>
  <li>Visualizes the resulting clusters.</li>
</ul>

<h2>📊 Output</h2>
<p>
The output includes a scatter plot with clearly separated clusters representing different customer segments. These clusters can be interpreted to understand the characteristics of each group and design targeted marketing strategies accordingly.
</p>

<h2>Features</h2>
<ul>
  <li>Data preprocessing and feature selection.</li>
  <li>Elbow method for optimal cluster selection.</li>
  <li>K-Means clustering implementation with scikit-learn.</li>
  <li>Visualization of customer segments.</li>
</ul>

<h2>Future Improvements</h2>
<ul>
  <li>Support for additional clustering algorithms (e.g. DBSCAN, Agglomerative Clustering)</li>
  <li>Interactive dashboard for exploring cluster characteristics</li>
  <li>Integration with real-world marketing tools</li>
</ul>

</body>
</html>
