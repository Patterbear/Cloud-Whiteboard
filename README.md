## Installation

Clone the repo and build the environment:
```
$ git clone https://github.com/greyli/twilio-whiteboard
$ cd twilio-whiteboard
$ python3 -m venv venv  # use "python -m venv venv" on Windows
$ . venv/bin/activate  # use "venv\Scripts\activate" on Windows
(venv) $ pip install -r requirements.txt
```

Create a file called `.env` and fill it with the twilio variables (distributed privately)

Run the application with:
```
(venv) $ flask run
```

Then open http://localhost:5000 on two or more tabs to test.
