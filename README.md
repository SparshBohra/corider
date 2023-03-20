# Corider-CRUD app
### backend APIs in flask

Python version: 3.11.2

1. SETUP & INSTALLATION

Make sure you have the said Python version installed.
```
git clone <repo-url>
```
```
source venv/bin/activate
```
```
pip install -r requirements.txt
```
Running The App
```
python app.py
```
Viewing The App

Go to ```http://127.0.0.1:5000``` or ```http://localhost:5000```.


2. USING DOCKER:

How to pull the docker image:
```
$ docker pull sparshbohra/corider:0.0.1.RELEASE
```
Build the image using the following command:
```
$ docker build -t sparshbohra/corider:0.0.1.RELEASE .
```
Run the Docker container using the command shown below:
```
$ docker run -d -p 5000:5000 sparshbohra/corider:0.0.1.RELEASE
```
The application will be accessible at http:127.0.0.1:5000 or if you are using boot2docker then first find ip address using ```$ boot2docker ip``` and the use the ip ```http://<host_ip>:5000```
