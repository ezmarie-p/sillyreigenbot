Must install:
- tweepy
- Pillow

in order to be able to run the script.

the script also needs a cred.json file containing all the tokens needed for the twitter API.

TODO: add template cred.json (too lazy rn)
TODO: include tweepy and Pillow in requirements if possible

Running script: 
python3 -m venv botenv

source botenv/bin/activate

pip install --upgrade pip

pip install -r requirements.txt

python main.py
