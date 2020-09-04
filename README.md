# a quick & simple video downloader

### setup
create virtual environment:
`python3 -m venv venv`

activate virtual environment:
Windows:
`venv\Scripts\activate.bat`
Unix or MacOS:
`source venv/bin/activate`

install requirements:
`pip install -r requirements.txt`

### usage
`python3 dl.py <url 1> <url 2> ... <url n>`

### done
deactivate the virtual environment:
`deactivate`

### current KeyError: 'cipher' fix
`pip install git+https://github.com/apdug/pytube3.git@5ac96de69f025b09abf2a6a24a4103c78b7e4c81 --upgrade`

### 'no module named pip' fix
`python3 -m ensurepip`

