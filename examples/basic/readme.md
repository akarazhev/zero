## Basic example of ZeroServer and ZeroClient

`server.py` has the ZeroServer. Exposing some methods at `localhost:5559`.

Call these methods from `client.py`.

### Run
From the project root directory

- Setup project
```
python3 -m venv venv
source venv/bin/activate
pip install -r examples/basic/requirements.txt
```

- Start the server
```
python -m examples.basic.server
```

- Run the client
```
python -m examples.basic.client
```
