# AutoBai

Created to even the playing field against scalpers. Damn near ruined Christmas. 

This script so far ONLY works on Walmart. But I plan on adding more features to this later. 

## Note:
This code was written for folks on either a linux system or a Mac. Sorry windows users, feel free to take this code and make it work with your own setup. 

Gather the tools you need below:

## Dev Tools
### Installments
* [Virtualenv](https://pypi.org/project/virtualenv/)
* [Python](https://www.python.org/)
* [Selenium](https://selenium-python.readthedocs.io/installation.html)
* [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)

# How to run:

After installing the things you need, setup your virtual enviornment and activate it: 
```
virtualenv venv --python=$(which python3)
source venv/bin/activate
```
Install the requirements
```
pip install -r requirements.txt
```
Make sure you have the chromedriver in your PATH. Take a look at the `constants.py` file. That's where I put my path. You can update the constant on your end with the right path to the chromedriver executable.

Make sure the chromedriver is executable:
```
(venv) kubrick-5995 :: ~/AutoBai ‹main*› % which chromedriver                                                                                                      
/usr/local/bin/chromedriver
(venv) kubrick-5995 :: ~/AutoBai ‹main*› %         
```
Run the script! It may be unresponsive at times, but that's okay. It's constantly refreshing walmart in the background. 

```
python Autobai_PS5_RELEASE.py
```
Or run one of the other ones. Explore, break it, fix it, have fun with it. 

## Planned Updates
* Add more sites. 
* Make the bot 'trainable'

# Notice:

Good luck. This will not guarantee anything, but it's worth a shot. Even if you weren't able to get a PS5, I hope this taught you something about automation and stuff. 
