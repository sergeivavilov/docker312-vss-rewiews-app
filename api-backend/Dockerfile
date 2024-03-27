FROM python:3.6
WORKDIR /app
COPY . .
EXPOSE 5000
RUN pip install --no-cache-dir -r requirements.txt
CMD [ "python", "app.py" ]