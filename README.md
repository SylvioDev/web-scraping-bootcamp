## Requirements
- Python 3.13
- Beautifulsoup 4
- Scrapy 2
- Selenium
  
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

