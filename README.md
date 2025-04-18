# Bias-Correction-for-Precipitation-Products-

⚠️ Important: To use other satellite products and download TIFFs from GEE, simply change the product name in the GEE script accordingly.

📘 README – IMERG Precipitation Bias Correction Using Linear Scaling

This project provides code for applying Linear Scaling bias correction to the IMERG precipitation product, along with tools for data retrieval via Google Earth Engine (GEE). The workflow is divided into three main stages:

🔹 1. Long-Term Statistics Calculation

📊 Calculates the long-term mean and variance of IMERG data.

These values are essential for performing the linear scaling correction.

🔹 2. Linear Scaling Bias Correction

⚙️ Applies linear scaling to adjust IMERG precipitation data for bias.

This method is demonstrated using IMERG as a sample dataset.

📥 Observed station data (from Excel) must be used to compute the observed mean.

✍️ The calculated observed mean should be manually entered into the second script before running the correction.

🔹 3. Model Evaluation & Visualization

📈 Evaluates the performance of the bias correction.

🖼️ Plots charts comparing raw vs. corrected IMERG data.

🌐 Google Earth Engine (GEE) Integration

✅ JavaScript code is included to retrieve IMERG data from GEE.

Run the script in the GEE Code Editor to download the necessary datasets.
