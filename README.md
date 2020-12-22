# Unit 13 Homework Assignment 
# Robo Advisor for Retirement Plans

# Background

In this project, I accomplish the following main tasks:

1. **Initial Robo Advisor Configuration**: Define an Amazon Lex bot with a single intent that establishes a conversation about the requirements to suggest an investment portfolio for retirement.

2. **Build and Test the Robo Advisor**: Make sure that the bot is working and responding accurately along with the conversation with the user, by building and testing it.

3. **Enhance the Robo Advisor with an Amazon Lambda Function**: Create an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This task includes testing the Amazon Lambda function and making the integration with the bot.

# Files

The **Robo Advisor** bot was exported and saved as zip file ***RoboAdvisor_BOT***.

The **Robo Advisor** bot is built on the **RecommendPortfolio** intent which was exported and saved as zip file ***RecommendPortfolio_INTENT***.  

The **riskLevel** slot was created within the **RecommedPortfolio** intent to accept the investor’s risk tolerance level. It was exported and saved as zip file ***riskLevel_SLOT***.

The **Robo Advisor** is enhanced with **recommendPorftolio** Amazon Lambda function which was saved as Python file ***robo_advisor.py***. The same function was also saved in Jupyter Notebook file ***robo_advisor.ipynb***.

The **recommendPortfolio** function was tested using the test cases contained in the folder ***Taste Cases***.

The performance of **Robo Advisor** was screen-recorded using Xbox Game Bar and the video file was saved as ***RoboAdvisor_LEX_BOT_VIDEO*** file.
