# InstaBot
An Instagram automation bot using Selenium. The bot can login, like, follow and comment on the posts

# Setup
- Install pip, it is used for downloading further python packages/libraries easily (you can install pip alongwith Python)
- Once you have pip, you need to install required libraries. Open command prompt or terminal depending on your OS, and run the following command

````
pip install selenium python-dotenv pandas
````
- Install either Geckodriver (if you want to run on Firefox) or Chrome driver (if you want to run on Google Chrome) from the drivers list here. Here, we are using Firefox
- Optionally, change the configuration variables of number of posts you want to engage and probability of commenting on a post in the configuration section at the top of instabot.py
- Don't forget to create a `.env` file and add id and pass variables to add your credentials as shown below:
````
id=yourusername
pass=yourpassword
````
# Running the script
All set, open command prompt or terminal and run the following code, the bot will start its job
````
./instabot.py
````

# Contribution
If you would like to improve the script, feel free to create a pull request


