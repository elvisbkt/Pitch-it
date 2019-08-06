# pitch-board

## BY Elvis Biketi https://github.com/elvisbkt/   05/08/19

## Description
This is a web app created using python flask.It allows users to submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.
also be able to comment and vote on another user's pitches.

## user stories
* view pitches
* login
* pitch
* downvote and upvote
* view personal pitches on profile
* comment on pitches
## BDD
| Behavior           | Input                 | Outcome                            |
| -------------------|-----------------------| -----------------------------------|
| request page       | click horuku link url | view othr pitches  & vote          |
| click on a pitch   |                       | vote/comment                       |
| sign in/up         | details pass & user   | view,pitch & comment               |

## Prerequisites
* Python3.6

## Setup/Installation Requirements
* Internet access
* git clone https://github.com/Emmasharon/best-pitch
* $ cd into pitch-perfect
* $ python3.6 -m venv virtual (install virtual environment)
* $ source virtual/bin/activate
* $ python3.6 -m pip install -r requirements.txt (install all dependencies)
* Inside the manage.py module change the config_name parameter from 'production' to 'development' ie app = * create_app('production') should be app = create_app('development')
* $ ./start.sh
* or click on this link and follow the steps in the BDD.
## Known Bugs

No known bugs

## Technologies Used
* Python3.6
* Postgressql
* flask bootstrap
* css
* html
## Support and contact details
contact elvisbkt@gmail.com for support.


### License

The project is licensed under MIT license https://opensource.org/licenses/MIT
Copyright (c) 2019, elvisbkt
### Language
Python
