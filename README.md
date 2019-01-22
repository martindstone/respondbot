# respondbot

Respondbot can automatically acknowledge and resolve incidents in your PagerDuty domain after a period time randomly chosen from a range you specify. It will always acknowledge and resolve as the currently assignes user.

## Installation:

* Clone this repo
* Create a python3 virtual environment: `python3 -m venv venv`
* Activate the virtual environment: `. venv/bin/activate`
* Install the dependencies: `pip install -r requirements.txt`
* Edit respondbot_config.json and add values for your PagerDuty domain
* `python ./respondbot.py`
* Share and Enjoy!
