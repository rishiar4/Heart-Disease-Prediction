# Heart-Disease-Prediction
Detecting Heart Disease

This is a machine learning project used to detect heart diseases using the previous details depending upon the conditions. This is an end to end project in python and written with the help of Flask and deployed using Heroku.

> ## Requirements:
> For Required package/module installation, open the terminal and copy paste below command:
> - pip install requirements.txt

> ## To Execute the code:
> Run the command in your terminal or command prompt.
> - python app.py \
> After running the the same, you will get your local host address, something like as shown below.
> ![image](https://user-images.githubusercontent.com/48138906/87266873-dea1fe00-c4e3-11ea-8a4a-f89f2cda54a2.png) \
> Open the same in your browser, the setup is now complete.

> The broswer opens to this.
![Screenshot from 2020-07-21 07-15-40](https://user-images.githubusercontent.com/48138906/88003273-159a9400-cb22-11ea-97c5-2ead46501711.png)

> After pressing the Predict button, the data is evaluated and then the result is shown on the same page.

> You can now detect the heart disease based on different features.
> ## prediction.ipynb
> This python notebook has the code for the machine learning model which is trained using the data provided in "data.csv", the model is then dumped using pickle and further used to predict values using Flask.
> This is a classification problem used to detect heart diseases and find if the user is suffering from a heart disease or not.
> I have used Random Forest Classifier machine learning model to work on the data. The accuracy of the model is 81% which can be increased with hyper parameter optimization or with the help of more data.
> I have used pickle to dump the model to further use it for deployment.
> ## Heroku
> I have used Heroku cloud services to deploy the same and the link for the same can be found here:
> https://predictingheartdisease.herokuapp.com/

> Do star the repository, also suggestions and changes are most welcome.

# Note:
 > Having a seperate environment setup is always expected to follow.
