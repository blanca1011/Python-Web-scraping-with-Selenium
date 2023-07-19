# Python-Web-scraping-with-Selenium

[Python Web-scraping with Selenium vs Scrapy vs BeautifulSoup | Witcher project ep. #1](https://www.youtube.com/watch?v=RuNolAh_4bU)

## Troubleshooting

**ModuleNotFoundError** <br>
* Install the module like the following
[pip install webdriver_manager](https://stackoverflow.com/questions/63421086/modulenotfounderror-no-module-named-webdriver-manager-error-even-after-instal)

**Unable to Locate Driver Error**  <br>
1. Read the [Selenium documentation](https://www.selenium.dev/documentation/webdriver/troubleshooting/errors/driver_location/) <br>
2. Check the version of installed Selenium through terminal <br>
    ```witcher_project % python3``` <br>
    ```>>> import selenium``` <br>
    ```>>> selenium.__version__``` <br>
3. Read the docs to [use Selenium 4 with Chrome](https://pypi.org/project/webdriver-manager/)
