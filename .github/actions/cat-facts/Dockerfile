FROM python3 -m venv tutorial-env

RUN tutorial-env\Scripts\activate.bat

COPY requirements.txt ./

RUN python -m pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "/src/main.py" ]
