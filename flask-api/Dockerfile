FROM python:alpine3.7
COPY . /app
WORKDIR /app
RUN pip install --upgrade pip    
# If getting pip upgrade error during image build, then uncomment the above line.
RUN pip install -r requirements.txt
ENV PORT 5000
# This sets the environment variable "PORT" to the value "5000". This could be used by the application inside the container to determine the port on which it should listen for incoming connections.
EXPOSE 5000
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
