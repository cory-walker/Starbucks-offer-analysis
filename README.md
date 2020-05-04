# Starbucks_promotion_recommendations
 This is my Data scientist capstone project for the Udacity Data Scientist nanodegree.<br>
 We clean, join, and analyze a dataset containing customer transactions, and offers made to them over a period of about 30 days.

### Installation
The code was written in a Jupyter notebook using Python 3.7.4<br><br>
<b>Jupyter notebooks</b>
<ul>
    <li>Starbucks_Capstone_notebook: main code workbook</li>
    <li>removed_powerset_code: removed code that ran through every combination of attributes used to generate Random Forest models, and then rate their accuracy</li>
</ul>
<b>Libraries</b>
<ul>
    <li>pandas version: 0.25.1</li>
    <li>numpy version: 1.16.5</li>
    <li>json version: 2.0.9</li>
    <li>statsmodel version: 0.10.1</li>
    <li>sklearn version: 0.21.3</li>
    <li>joblib version: 0.13.2</li>
    <li>matplotlib</li>
    <li>math</li>
    <li>datetime</li>
</ul>
<b>Data</b>
<ul>
    <li>portfolio.json: containing offer ids and meta data about each offer (duration, type, etc.)</li>
    <li>profile.json: demographic data for each customer</li>
    <li>transcript.json: records for transactions, offers received, offers viewed, and offers completed</li>
    <li>RandomForest_Iteration_results.csv: Result set from running all possible iterations of Random Forest features</li>
</ul>
<b>Models</b>
<ul>
    <li>bogo_RandomForest_Model: Bogo offers Random Forest model saved as a pkl file</li>
    <li>discount_RandomForest_Model: Discount offers Random Forest model saved as a pkl file</li>
    <li>informational_RandomForest_Model: Informational offers Random Forest model saved as a pkl file</li>
</ul>

### Usage
This repository was made so both the Udacity team, and potential employers could review this work easily. If you use my work as a learning aid, I hope it is helpful