FROM python:3

RUN python3 -m venv tutorial-env

COPY requirements.txt ./

RUN python -m pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "/src/main.py" ]
