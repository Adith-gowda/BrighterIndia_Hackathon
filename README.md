# BrighterIndia_Hackathon

# Problem Statement
Any electoral party, would be in a state of apprehension right before the ection results are out. During such times the first view that one approaches is the social media. Since word spreads faster in today’s world of technology, it is evident that one would turn to the most widespread platform in the world. Analysing metrices using social media platforms is quite hectic due to the rapid turnaround of information. This concern is widespread among the majority of political parties and is a common worry shared by any candidate running for election.
This is the very issue that we aim to tackle, along with other issues that revolve around addressing the prevalent challenges faced by political parties and candidates during election periods. Our goal is to find effective solutions to enhance their public perception, engage with voters, and overcome the hurdles that hinder their success in the democratic process. By focusing on this issue, we seek to empower political entities and candidates to strengthen their position, build trust with the electorate, and foster a more vibrant and inclusive democratic landscape.

# Our Approach
So what we are basically trying to do is, create a Machine Learning model which can take a certain post/comment and predict its demographic along with its positivity or negativity with respect to the party. The model itself is trained based on the electoral tweets of 2019, within a certain time period right before the results of the election. This gives the worst case scenario for the model to be tested, the model is based on the Naïve Bayes Algorithm for Sentiment Analysis. The model also involves visualization which gives the demographic for each and every party, down to the region and count of votes for the both men and women. 

# Product's User Interface
![image](https://github.com/Adith-gowda/BrighterIndia_Hackathon/assets/95766897/590bdee6-800f-42c0-82db-95ef5d17aadc)
![image](https://github.com/Adith-gowda/BrighterIndia_Hackathon/assets/95766897/ce6b73b4-e9bd-4d97-bb45-11e3715b98f1)

# Grdio UI
As for the visualization of the trained model we use a package provided by Python libraries, knowns as Gradio.

Gradio is a Python package. It is an open-source library that you can install and use in your Python environment. Gradio allows you to turn your machine learning models into user-friendly web apps without much coding. It supports various input types like text, images, and audio, and it displays model predictions on a web interface. With Gradio, you can easily share and deploy your models so that anyone can interact with them through a web browser without needing to know how to run Python code.

