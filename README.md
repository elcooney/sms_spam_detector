# sms_spam_detector
Module 21 Challenge  
*Elizabeth Cooney* ***10/28/2024***

## Overview
>You'll be refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, you will create a Gradio app to host the application, enabling users to test text messages. The application will provide feedback to users, indicating whether the text is classified as spam or not, based on the model's performance.

### Steps:
1. Create the SMS Classification Function
    - Using the code in the sms_text_classification_solution.ipynb file, create the sms_classification function in the gradio_sms_text_classification.ipynb
    - Load the SMSSpamCollection.csv into a DataFrame and call the sms_classification function with the DataFrame, and set the result to the "text_clf" variable.
2. Create the SMS Prediction Function  
    - Use the sms_prediction function to predict the classification of a new text 
3. Create the Gradio Interface Application
    - Create a Gradio Interface application that takes a textbox for the inputs and has a textbox for the output
    - Launch the application and provide the URL to share the application
    - Test the following messages:
        1. You are a lucky winner of $5000!
        2. You won 2 free tickets to the Super Bowl.
        3. You won 2 free tickets to the Super Bowl. Text us to claim your prize.
        4. Thanks for registering. Text 4343 to receive free updates on medicare.

*Prompt provided via Edx Bootcamp* [here.](https://bootcampspot.instructure.com/courses/5758/assignments/80795?module_item_id=1266028)


## Resources
*Code completed for Challenge 21 was modified from the challenge files provided by Edx Bootcamp:*  
Download **Module 21 Challenge Files** [here](https://static.bc-edx.com/ai/ail-v-1-0/m21/lms/starter/M21_Starter_Code.zip).
The unedited starter code is also located in "M21_Start_Code" folder. 


## Usage Instructions

1. **Setup:** Install Python, Jupyter Notebook, and necessary libraries (including Pandas, Gradio, and sklearn)
2. **Data:** Ensure access to Module 21 Challenge Files. 
3. **Code:** Refer to the provided Jupityr Notebook named "***gradio_sms_text_classification.piynb***", in the main repository folder for implementation details.
4. **Execution:** Run the code to analyze and visualize results.