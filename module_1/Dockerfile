#from python container add pands to it and have the entrypoint as bash

FROM python:3.9 

RUN pip install pandas


#copy our file from local ti docker image and specify the working directory as app
WORKDIR /app
COPY pipeline.py  pipeline.py

#ENTRYPOINT [ "bash" ]

ENTRYPOINT [ "python","pipeline.py" ]

