# cloud-native project management service
## Getting started

Create a `.env` file. You can copy the `.env.example` file, 
```sh
cp .env.example .env
```

Setup your python virtual environment
```sh
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Source .env and go
```sh
source .env
flask run
```