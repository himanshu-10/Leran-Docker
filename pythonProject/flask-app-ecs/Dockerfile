#fetch base image 

FROM python:3.7 

# working directory
WORKDIR /add

#coping code from local machine to container 

COPY . .

#Installation of dependecy like requirement file
RUN pip install -r requirements.txt


# run the app while container is start or run
CMD ["python","run.py"]

