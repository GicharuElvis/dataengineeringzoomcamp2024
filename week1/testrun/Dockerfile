FROM python:3.9

# install pre requisites
RUN pip install pandas
# folder you want the configuration to take place
WORKDIR /app

# file you want to run and the name of the file in the container
COPY pipeline.py pipeline.py

# where you want to enter from....
ENTRYPOINT [ "python","pipeline.py" ]
