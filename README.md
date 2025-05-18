# 🛒 Amazon Automation Testing using Python & Selenium

This project automates the login process on [Amazon.in](https://www.amazon.in) using **Python** and **Selenium WebDriver**. It simulates user interactions with the browser, like hovering over the login button, entering credentials, and clicking the sign-in button.

> ⚠️ **Disclaimer**: This project is for educational purposes only. Automating real websites like Amazon may violate their terms of service. Do not misuse automation on live websites.

---

## 📌 Features

* Automates opening the Amazon India website
* Simulates mouse hover to reveal the login option
* Automatically fills in the email and password fields
* Clicks on the login button to sign in

---

## 🚀 Technologies Used

* Python 3.x
* Selenium WebDriver
* ChromeDriver
* Chrome Browser

---

## 🔧 Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/amazon-automation-testing.git
   cd amazon-automation-testing
   ```

2. **Install Dependencies**

   ```bash
   pip install selenium
   ```

3. **Download ChromeDriver**

   * Download the [ChromeDriver](https://sites.google.com/chromium.org/driver/) that matches your browser version.
   * Place it in the path mentioned in your script (or update the path in the code accordingly).

4. **Create a `logindata.py` file**

   This file stores your login credentials securely.
   Create a new file named `logindata.py` and add:

   ```python
   USERNAME = "your-email@example.com"
   PASSWORD = "your-password"
   ```

   > 🔒 **Important:** Do **NOT** upload this file to GitHub.

5. **Run the Script**

   ```bash
   python amazon_login_automation.py
   ```

---

## 📁 File Structure

```
amazon-automation-testing/
│
├── amazon_login_automation.py    # Main script to perform login automation
├── logindata.py                  # Contains login credentials (not for upload)
└── README.md                     # Project documentation
```

---

## 📚 Learning Outcomes

* Hands-on experience with Selenium for browser automation
* Understanding of XPath and web element selection
* Basic automation practices and credential handling
* Applying delays and action chains to simulate real user behavior

---

## ✅ Future Enhancements

* Add automated product search and add-to-cart functionality
* Improve error handling and dynamic wait instead of fixed `time.sleep()`
* Integrate test cases using `unittest` or `pytest`
* Add reporting for pass/fail login attempts

---

##📜 License

This project is open-source and available for educational use. Do not use for scraping or violating website terms.
