# saucedemo
python and selenium automation




Prerequisites to Run the Code

1. Install Dependencies
Ensure you have Python 3.6+ installed.

Then, set up a virtual environment (optional but recommended):

# Create virtual environment
copy -> python -m venv venv

# Activate virtual environment
# macOS/Linux: source venv/bin/activate
# Windows: venv\Scripts\activate

Install required libraries:

Copy -> pip install -r requirements.txt
If you don't have requirements.txt, run:
Copy -> pip install selenium webdriver-manager pytest

2. WebDriver
Install the appropriate WebDriver for your browser (ChromeDriver for Chrome or GeckoDriver for Firefox). Alternatively, webdriver-manager handles this automatically.

3. Running Tests
Run your tests with pytest:

Copy -> pytest tests/
To run the script directly, use:

Copy -> python test_saucedemo.py
