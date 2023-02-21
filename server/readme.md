## Get Started

1. Clone or download the project on your computer

2. Make copy of `.env` file from `.env.example` and add environment variables 

#### Windows

3. Create and activate a virtual environment  
```python
python -m venv .venv
.venv\Scripts\activate
```

4. Install dependencies  
```python
pip install -r requirements.txt
```

5. Run the server locally  
```python
python app.py
```

#### Linux/MacOS

3. Create and activate a virtual environment
```python
python -m venv .venv
source .venv/bin/activate
```

4. Install dependencies
```python
pip install -r requirements.txt
```

5. Run the server
```python
python app.py
# or
export FLASK_APP=app.py
flask run
```