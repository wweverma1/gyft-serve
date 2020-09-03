# gyft-serve

Flask frontend for gyft

Website at [https://gyft.metakgp.org/](https://gyft.metakgp.org/)

*gyft* is located at [metakgp/gyft](https://github.com/metakgp/gyft)

This would download your `timetable.ics` file, import to Google Calendar by following this [link](https://support.google.com/calendar/answer/37118?hl=en).

## Demo

![placeholder](out.gif)

## Development & Deployment

## Running Locally

Please follow the following steps to run the application locally.

NOTE: The instructions assumes that you are using a linux system (specifically Debian based distribution).

### First Time Setup

0. Clone the repository `git clone https://github.com/metakgp/gyft-serve`
0. Change directory to the clone repository.
0. [Install Python3.7](https://linuxize.com/post/how-to-install-python-3-7-on-ubuntu-18-04/)
0. [Install pipenv](https://pipenv-fork.readthedocs.io/en/latest/install.html)

### Running In Virtual Environment

0. Run `pipenv shell` (to create a virtual environment for the program)
0. Run `pipenv install --dev` (to install all the dependencies)
0. Run `gunicorn app:app --log-file=-` (to launch the application)

### What To Do Every Sem?

We need to updates dates.py every semester.

This repository just serves as a frontend for [original Gyft](https://github.com/metakgp/gyft/) and is mostly maintained alongside updates to the original repository.


NOTE: **The `master` branch is auto deployed on Heroku**.
