# portfolioClassification
This is a piece of portfolio over which I tackle a classification problem with Machine Learning

## Install Virtual Environment
Run this on your command line inside project root directory to create the virtual env:
python3 -m venv .env

Then run to activate the created virtual env:
(LINUX)     .env/bin/activate
(WINDOWS)   ./.env/Scripts/activate.bat (OR run activate.bat)

And then run the command below to install all packages necessary:
python3 -m pip install -r requirements.txt

Then, to open jupyter with the selected venv, execute:
jupyter notebook

## About the data
The database used in this project is called Fetal Health database and comes from the following Kaggle competition: https://www.kaggle.com/andrewmvd/fetal-health-classification

The main variable is "fetal_health", in which the condition "1" represents a baby with normal health, the condidtion "2" represents a baby with suspected ill health condidtion, and the condition "3" represents a baby with pathological health condidtion.