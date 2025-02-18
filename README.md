Building a Regression Model

TikTok
TikTok logo
Project goal:

The TikTok data team is developing a machine learning model for classifying claims made in videos submitted to the platform.

Background:

TikTok is the leading destination for short-form mobile video. The platform is built to help imaginations thrive. TikTok's mission is to create a place for inclusive, joyful, and authentic content–where people can safely discover, create, and connect.

Scenario:

The data team at TikTok is close to their goal of building a model to assist in the classification of claims in videos. The next step is to use the project data to create a regression model. As a member of TikTok’s data team, you'll determine the type of regression model that is needed and develop one using TikTok's claim classification data.

Course 5 tasks:

Import relevant packages and TikTok data

Exploratory data analysis and check model assumptions

Determine the correct modeling approach

Build the regression model

Background on the TikTok scenario 
At TikTok, our mission is to inspire creativity and bring joy. Our employees lead with curiosity and move at the speed of culture. Combined with our company's flat structure, you'll be given dynamic opportunities to make a real impact on a rapidly expanding company, and grow your career.

TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider in a timely manner. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

Project background
TikTok’s data team is working on the claims classification project. The following tasks are needed at this stage of the project:

Determine the correct modeling approach

![image](https://github.com/user-attachments/assets/ff61e876-0302-4a52-82f2-1f3b3ee32a51)
![image](https://github.com/user-attachments/assets/1e54b2cb-46ad-42d6-b178-9c0bea02e3c8)
![image](https://github.com/user-attachments/assets/c79f902f-dc64-4d41-b0c0-41fe4d304312)
![image](https://github.com/user-attachments/assets/f89c0105-dedb-4905-933b-cd9968cff909)
![image](https://github.com/user-attachments/assets/c85f01ef-3221-45ad-8052-e222601473ed)
![image](https://github.com/user-attachments/assets/aa611240-ba82-4e00-960d-a1bdf2052f23)

Build a regression model

![image](https://github.com/user-attachments/assets/dc344a45-9220-4a26-9a55-39aaa92a11a5)


![image](https://github.com/user-attachments/assets/051b8fda-4ead-4a5f-b714-4bd9dac2d3c4)


Finish checking model assumptions

![image](https://github.com/user-attachments/assets/4a4a2764-cbc1-4f19-995d-b30a37e40010)

Evaluate the model


![image](https://github.com/user-attachments/assets/774b53dd-cc8a-4f21-81f7-e8e42c3b8f07)



Interpret model results and summarize findings for cross-departmental stakeholders within TikTok

Your assignment
You will create a regression model for the claims classification data. You'll determine the type of regression model that is needed and develop one using TikTok's claim classification data.

Specific project deliverables
With this end-of-course project, you will gain valuable practice and apply your new skills as you complete the following:

Course 5 PACE Strategy Document to consider questions, details, and action items for each stage of the project scenario

Answer the questions in the Jupyter notebook project file

Create a regression model

Evaluate the model

Create an executive summary to share your results 

 The data has some highly correlated variables so I dropped the column video_like_count from the
 model. It could have led to some multicollinearity issues when fitting the model. The model wasn’t
 the best and could probably be better. 0.61 precision, but .84 recall isn’t too bad.
 The longer the video the higher the likelihood of the user being verified. The model had decent
 prediction but, I would move on to trying a different model or a Neural Network.
