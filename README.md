# Intro to Data Science by Blueprint

**Presented by: Simran Jassal and Christopher Luc**

Hi there! Please do the following pre-reqs below before the workshop so we can get started right away! Feel free to message us if you have any issues. Also like our [Facebook Page](https://www.facebook.com/uwblueprint/) and check out our [website](https://www.uwblueprint.org/)!

**Slides:** Will be posted after the talk

**Additional Resources:** Will be posted after the talk

## Set up for Windows

1. checkout the readme on the [windows branch](https://github.com/uwblueprint/blueprint_intro_to_data_science/tree/windows#set-up-for-windows) for more details
1. when you git clone remember to switch branches `git checkout windows`

## Set up for Ubuntu

1. Same as Mac except in addition to `pip install -r requirements.txt` also run `sudo apt-get install libgeos-dev`

## Set Up for Mac

1. Install [Python 2.7](https://www.python.org/downloads/)
1. Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
1. Clone this repo and go into the root directory of this project
    1. Open Terminal
    1. Run `git clone https://github.com/chrisjluc/blueprint_intro_to_data_science`
    1. Run `cd blueprint_intro_to_data_science`
1. Install [pip](https://pip.pypa.io/en/stable/installing/)
    1. Run `python get-pip.py` in the root directory of this project
    1. Make sure `pip` is on the latest version, run `pip install --upgrade pip`
1. Set up and activate [virtualenv](https://virtualenv.pypa.io/en/stable/installation/).
    1. Run `sudo pip install virtualenv` in the root directory of this project
    1. Run `virtualenv env`
    1. Run `source env/bin/activate`
1. Install libraries into virtual environment
    1. Run `pip install -r requirements.txt`
    1. This can take anywhere from 5 - 20 minutes to run
    1. Run `source env/bin/activate` again
1. Connect to jupyter server
    1. Run `jupyter notebook`
    1. ipython notebook will output a URL that you can connect to on your browser.
        1. i.e. It will look like this `http://localhost:8889/?token=86b9639019c700265090b665dc3ecea89815bfcb573229c9`
    1. Connect to server by going to the link on your browser
1. Run test notebook to make sure everything is installed properly!
    1. Find the `Test Notebook.ipynb` and open it
    1. Open `Kernel` dropdown and select `Restart & Run All`
    1. You should see `SUCCESS!` at the bottom of the notebook
