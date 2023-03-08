# Souchkova Angelina
### QA Engineer

Linkedin: [Angelina Souchkova](https://www.linkedin.com/in/angelina-souchkova/)\
Phone number: +48572281408\
Gmail: Angelina.Souchkova@gmail.com
## Some information about me:
I studied at BNTU for 3 years, but dropped out due to a change of residence. I’ve finished a course of software testing. I very much liked to be engaged in testing and I plan to devote it the closest part of my life, to be improved, progress and develop in
the sphere of information technologies. I actively study programming languages, such as JavaScript, Python, SQL. I want to develop in the field of IT and switch to automated testing.

## Test-related skills:
* Test cases execution;
* Test cases creation;
* Test report creation;
* Tracking bugs into JIRA and Trello;
* Working with DataBase using SQL;
* Bug reporting and bug verification;
* Result analyzing.

## Programming related skills:
* Basics of Python
* Basics of JavaScript
* Git/GitHub

### As I said before, I want to move to automated testing. 
### Here is an example of an automated test, using Selenium and Python:
```
import math from selenium import webdriver
from selenium.webdriver.common.by import Byfrom selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as ECimport time
def calc(x):
  return str(math.log(abs(12*math.sin(int(x)))))
try:    
    link = "http://suninjuly.github.io/explicit_wait2.html"
    browser = webdriver.Chrome()    browser.get(link)
    price = WebDriverWait(browser, 12).until(
        EC.text_to_be_present_in_element((By.ID, "price"), "$100")    )
    button = browser.find_element(By.CSS_SELECTOR, "[id='book']")
    browser.execute_script("return arguments[0].scrollIntoView(true);", button)
    button.click()
    x_element = browser.find_element(By.CSS_SELECTOR, "span[id='input_value']")    
    x = x_element.text
    y = calc(x)
    value = browser.find_element(By.CSS_SELECTOR, "[id='answer']").send_keys(y)
    submit = browser.find_element(By.CSS_SELECTOR, "[type='submit']")
    browser.execute_script("return arguments[0].scrollIntoView(true);", submit)
    submit.click()
finally:    time.sleep(10)
    browser.quit()
```
## Education:
* __Belarusian National Technical University__ The faculty of energy. Not completed.
* __Stormnet__ Softwear testing. Completed: may 2022.
* __EPAM Learning__ IT Fundamentals to beginers.
* __Codeacademy__ Python3, SQL.
* __Stepik__ Test automation with Selenium and Python.
* __Hexlet__ Python basics.


## English level: B1 (Intermediate). Referring to the results of the English test from EPAM University.

