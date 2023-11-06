FROM python:alpine3.7
COPY . /app
WORKDIR /app
#RUN pip install --upgrade pip    # If getting pip upgrade error during image build, then uncomment this line.
RUN pip install -r requirements.txt
ENV PORT 5000
EXPOSE 5000
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
