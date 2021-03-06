# scorer.py
A simple python script to fetch cricket scores and send notifications.

## Features ##
* Allows you to choose from concurrent matches
* Change choice by Ctrl+C
* Quit by Ctrl+C twice
* Shows notification only if there's a change in the score (run or wicket)
* Should work with python2 or python3

## Requirements ##
* Install python dependencies using `pip install -r requirements.txt`
* libnotify, BeautifulSoup
* Internet connection

## Usage ##
python scorer.py

## Credits ##
* [CricInfo](http://www.espncricinfo.com/) for providing score
* [Anubhav Yadav](http://www.quora.com/What-are-some-cool-Python-tricks/answer/Anubhav-Yadav-5) for initial code and idea
* [Akshay S Dinesh](https://github.com/asdofindia)
