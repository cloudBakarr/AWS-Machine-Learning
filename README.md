# AWS-Machine-Learning

This project consist of an AWS S3-hosted Database holding a dataset that we will train and test our machine learning model on.

Then we have an EC2 instance running a Streamlit server that has all the inner-workings of our Python Web App.

The web app then import our data from AWS S3, then apply some data preprocessing, then allow us to view some visualizations about the soccer data, and also view some behavior of the players on the soccer field for example.

We then use machine learning models that would learn from the imported soccer dataset and maybe recommend a specific player in a specific situation or maybe predict a new game result based on previous games in the dataset.

All the Web App's code is synced to this GitHub repo and developed into a Continuous Integration and Delivery pipeline that would automatically deploy any commits to our main branch on the GitHub repo to our hosted Web App with no downtime or manual updating on our EC2 Streamlit server!
