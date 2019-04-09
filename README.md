# Forked from Frint0; My Updates:  
* Added LinkedIn email enumeration

# Email-Enum
[![Version](https://img.shields.io/badge/Version-v1.1-brightgreen.svg)](https://shields.io/)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)](https://shields.io/)
[![Platform](https://img.shields.io/badge/Platform-Linux/Windows-lightgrey.svg)](https://shields.io/)
[![Browser](https://img.shields.io/badge/Browser-Firefox-brightgreen.svg)](https://shields.io/)
[![Made with Python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

**Email-Enum searches mainstream websites and tells you if an email is registered!**

![Demo Photo](https://raw.githubusercontent.com/Frint0/email-enum/master/demo.png)

## Dependencies
* Firefox
* Selenium => 3.14
* Click => 7.0
* Termcolor => 1.1
* PyFiglet => 0.8

## Installation
### Linux

```
git clone https://github.com/Frint0/email-enum.git
cd email-enum
chmod +x setup.sh
./setup.sh
```

### Windows (Docker)

```
docker build -t emailenum .
docker run --rm -it emailenum <target email>
```

## Usage

`python3 check.py email@gmail.com` or `./check.py email@gmail.com`

## To-Do's

* More Websites
* Username Enumeration
* Increased Verbosity
* More arguments
* Non-Headless mode

*and much more...*

## Disclaimer

This program is done entirely via web scraping, if a website changes its element variables or layout, you might need to wait for an updated version of Email-Enum or feel free to contribute.
