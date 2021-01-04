# Roboadviser
Creating a RoboAdvisor using Amazon Lex and Amazon Lambda

In this homework, I configured a Roboadvisor using an Amazon Lex chatbot that provides an investment allocation recommendation for retirement. To enhance the chatbot, I created an Amazon Lambda Function that validates the user's inputs (age and invesetment amount) and gives out an investment recommendation based on the user's risk level. 

The user must have the following inputs:
- age must not be greater than 65 years old
- investment amount must be at least $5000

The GIF below shows how the roboadviser chatbot works. I also used some test cases with non qualified user inputs (age >65 or investment <5000) to show how the roboadviser responds.



Below is a GIF that shows how the roboadviser works:

![gif](Images/finalfinalversion.gif)




Here are the relevant files for reference:

- [Lambda Function in Python](https://github.com/nikanikachan/unit13-challenge/blob/main/RoboAdvisor/lambda_function_hw.py) 
- [Robo Advisor zip file from Amazon Lex](https://github.com/nikanikachan/unit13-challenge/blob/main/RoboAdvisor/RoboAdvisor_1_3166e1ec-98c2-4287-be4a-a3287e6d3a56_Bot_LEX_V1.zip) 

