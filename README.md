# Derivatives Pricing App
 - By Dannie Chen

## a. Description
This repo contains an API and UI to price different types of call options and call spreads. The backend and frontend can be found in this repository. The tool used to build the webserver and web UI is Python flask.
## b. Installation
First make sure that you have python3 and pip3 installed.
Next, install virtualenv if you haven't.
```python
$ pip3 install virtualenv 
```
In project folder, run
```python
$ virtualenv -p python3 venv
```
to initialize python virtual environment.
Activate virtual environment with:
```python
$ source ./venv/bin/activate
```
Install flask in venv
```python
(venv)$ pip install flask
```
App is ready to run:
```python
(venv)$ python app.py
```
Visit http://127.0.0.1:5000 to view the Web UI locally.

## c. Project requirements
Create a secure API and UI using the tools and languages of your choice to quickly price a call option and a call spread
## Usage
### Screenshots of the Web UI
![Alt text](/pricing.png?raw=true "User Interface")
## Release Planning
- Add other pricing models (e.g. Heston SV model, Monte Carlo Simulation) to price call options;
- Add pages for more advanced and complex derivatives (e.g. discrete barrier callable notes, derivatives with path dependency features);
- Add visualization (e.g. line graphs) for price changes of each derivative as expiration nears;
- Make the User Interface more aesthetically pleasing.
## Roadmap or what you would improve on if you had more time
