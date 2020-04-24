# AutoPost-FB

This `Python` script uses `Selenium` for automating browsing and logging to facebook using users credentials and posts `Happy Birthday` to everyone who has a birthday on the current day. It runs on a Firefox browser using the `Geckodriver`.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Selenium.

```bash
pip install selenium
```
Latest [Geckodriver](https://github.com/mozilla/geckodriver/releases) download and unzip to current working directory.

## Usage

```from selenium import webdriver
from selenium.webdriver.common.keys import Keys
import getpass

id = input('Enter your Email ID or Phone No. - ')
key = getpass.getpass('Enter your Password - ')
driver = webdriver.Firefox(executable_path="folder_path/geckodriver")

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
