# Flask_deployment
![Screenshot (20)](https://user-images.githubusercontent.com/47673623/88183390-0c5b1580-cc4f-11ea-9d52-ec15811b2e02.png)

his is a demo project to elaborate how Machine Learn Models are deployed on production using Flask API

### Prerequisites
You must have Scikit Learn, Pandas,Joblib (for Machine Leraning Model) and Flask (for API) installed.

### Project Structure
This project has four major parts :
1. app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
2. templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.
3.Model - model.sav file where I developed the model

### Running the project
1. Ensure that you are in the project home directory. Create the machine learning model by running below command -

python app.py

By default, flask will run on port 5000.

3. Navigate to URL http://localhost:5000

You should be able to view the homepage as above !!!

4.Just put your country name and gdp/captia and you will get the life statisfaction index as below

![Screenshot (20)_LI](https://user-images.githubusercontent.com/47673623/88183981-cb173580-cc4f-11ea-8104-d7f867300b00.jpg)





