FROM python
ADD . /code
WORKDIR /code 
COPY /src/requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY /src/. .
CMD ["python3", "-m" , "flask", "run", "--host=0.0.0.0"] 
