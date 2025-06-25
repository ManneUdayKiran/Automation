
# Instagram Profile Scraper (cbitosc)

This Python automation script uses Selenium to log in to Instagram, visit a public profile (like [`@cbitosc`](https://www.instagram.com/cbitosc/)), and extract key account details such as bio, number of posts, followers, and following. The details are saved into a text file.

## 🔧 Features


- Automatically navigates to the target profile
- Extracts:
  - Username
  - Number of Posts
  - Followers
  - Following
  - Bio/Description
- Saves the output to `cbitosc_profile.txt`

## 🛠️ Setup

1. **Install dependencies**

```bash
pip install selenium
````

2. **Download ChromeDriver**

* Match your Chrome browser version: [https://sites.google.com/chromium.org/driver/](https://sites.google.com/chromium.org/driver/)

3. **Update the script**

Replace these placeholders with your Instagram credentials:

```python
USERNAME = 'your_username'
PASSWORD = 'your_password'
```

4. **Run the script**

```bash
python Automation.py
```

## 📁 Output

A file named `cbitosc_profile.txt` will be created with content like:

```
Name: cbitosc
Posts: 42
Followers: 2,345
Following: 5
Bio: CBIT Open Source Community | Empowering students through open collaboration.
```

## 🔐 Notes

* Use a **test Instagram account** to avoid login issues or being rate-limited.
* Instagram's UI may change, so class names or XPaths might need updates.
* This script is for educational and non-commercial use only.

## 📄 License

MIT License


