<div align="center"> 
  <a href="https://www.rocketseat.com.br/eventos/nlw/">
    <img
      src="https://www.rocketseat.com.br/eventos/nlw/_next/static/media/nlw-header-logo.2e1779ba.svg"
      width="322"
      height="auto"
    />
  </a>
</div>

# NLW Expert (Python) ![Python Logo](https://www.rocketseat.com.br/eventos/nlw/_next/static/media/python.8c4574ca.svg)

## Project
This project was developed as part of the NLW Expert event organized by Rocketseat. It is an API using Flask and Barcode. 
The endpoint will validate, and create an PNG image with a barcode.

## Features

- Users can create polls;
- Community members can vote on polls;
- Real-time updating of votes and ranking;
- API-based architecture for easy integration;

## Requirements
- Docker
- NodeJS

- ## TechStack
- Python
- Flask
- Cerberus (validator)
- Pre-commit (git hook)
- Pylint
- Pytest
- Python-barcode
- Virtualenv
- Pillow

## Setup
- Clone the repository
```bash
git clone https://github.com/Fcruz10/BarCodeGenerator.git
```
- Install dependencies
```bash
 pip install -r requirements.txt
```
- Run application
```bash
 py .\run.py
```
- For unit testing run
```bash
 pytest
```

## Useful Commands
- Activate the virtual environment
```bash
.venv/bin/activate
```
- Install Python packages
```bash
pip install <SOMETHING> (or pip3 install <SOMETHING>)
```
- Execute Python script
```bash
python run.py (or python3 run.py)
```
- Generate a file that contains the names and versions of all the installed packages
```bash
pip freeze > requirements.tx (or pip3 freeze > requirements.tx)
```
- Run automated tests written using the pytest framework
```bash
pytest
```

# Endpoints:
*  POST `/create_tag`
receives a body: `{"product_code": "string"}`
    * If sent on body `"tag_type": "qrcode"` the tag will be generated as qrcode

<br />
<p align="center"> Made by Francisco Cruz <a href="https://www.linkedin.com/in/francisco-cruz-074208140/"> Get in touch! </a> </p>
