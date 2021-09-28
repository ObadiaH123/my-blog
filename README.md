Blog Website
#### Author: [Benard Kiprotich Bett](https://github.com/kelvinrono)
## Description
This application enables individual to read different blogs written by different people. Also one can register as the writed and will be posting blogs 
As a user of the web application you will be able to:
1. View posted blogs
2. Comment on posted blog
3. Subscribe for notifications

As the writer, you will be able to
1. Register and sign in to the application
2. Post a blog
3. Delete insulting comments

## Setup and installations
* Clone Project to your machine
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements file.
* On your terminal run `python3.8 manage.py runserver`
* Access the live site using the local host provided
## Getting started
### Prerequisites
* python3.8
* virtual environment
* pip
#### Clone the Repo and rename it to suit your needs.
```bash
git clone https://github.com/kelvinrono/blog
```
#### Initialize git and add the remote repository
```bash
git init
```
```bash
git remote add origin <your-repository-url>
```
#### Create and activate the virtual environment
```bash
python3.8-venv virtual
```
```bash
source virtual/bin/activate
```
#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`
#### Make and run migrations
```bash
python3.6 manage.py check
python manage.py makemigrations news
python3.6 manage.py sqlmigrate news 0001
python3.6 manage.py migrate
```
#### Run the app
```bash
python3.6 manage.py runserver
```
Open [localhost:5000](http://127.0.0.1:5000)
## Testing the Application
`python3.8 manager.py tests`
## Built With
* [Python3.8](https://docs.python.org/3/)
* Flask
* Boostrap
* HTML
* CSS


## Support and contact details
For any support | corrections | consultantions and other related inquiries kindly Send me a Mail through kiprotichbernard780@gmail.com
### License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
Copyright (c) 2021 Moringa school

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files , to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

