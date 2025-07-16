## Requirements
- Python 3.13
attrs==25.3.0
Automat==25.4.16
beautifulsoup4==4.13.4
bs4==0.0.2
certifi==2025.7.14
cffi==1.17.1
charset-normalizer==3.4.2
colorama==0.4.6
constantly==23.10.4
cryptography==45.0.5
cssselect==1.3.0
defusedxml==0.7.1
fake-useragent==2.2.0
filelock==3.18.0
greenlet==3.2.3
h11==0.16.0
hyperlink==21.0.0
idna==3.10
incremental==24.7.2
iniconfig==2.1.0
itemadapter==0.11.0
itemloaders==1.3.2
jmespath==1.0.1
lxml==6.0.0
markdown-it-py==3.0.0
mdurl==0.1.2
mypy==1.17.0
mypy_extensions==1.1.0
numpy==2.3.1
outcome==1.3.0.post0
packaging==25.0
pandas==2.3.1
parsel==1.10.0
pathspec==0.12.1
playwright==1.53.0
pluggy==1.6.0
Protego==0.5.0
pyasn1==0.6.1
pyasn1_modules==0.4.2
pycparser==2.22
PyDispatcher==2.0.7
pyee==13.0.0
Pygments==2.19.2
pyOpenSSL==25.1.0
PySocks==1.7.1
pytest==8.4.1
python-dateutil==2.9.0.post0
python-dotenv==1.1.1
pytz==2025.2
queuelib==1.8.0
requests==2.32.4
requests-file==2.1.0
rich==14.0.0
ruff==0.12.3
Scrapy==2.13.3
selenium==4.34.2
service-identity==24.2.0
setuptools==80.9.0
six==1.17.0
sniffio==1.3.1
sortedcontainers==2.4.0
soupsieve==2.7
tldextract==5.3.0
trio==0.30.0
trio-websocket==0.12.2
Twisted==25.5.0
typing_extensions==4.14.1
tzdata==2025.2
urllib3==2.5.0
w3lib==2.3.1
websocket-client==1.8.0
wsproto==1.2.0
zope.interface==7.2

# 1. Clone the repository
git clone https://github.com/SylvioDev/web-scraping-bootcamp.git
cd web-scraping-bootcamp

# 2. Create & activate a virtual environment
python -m venv .venv
source .venv/Scripts/activate.ps1          

# 3. Install the exact, locked dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
# 4. Run the tests
pytest

