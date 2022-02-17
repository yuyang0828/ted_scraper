
how to install selenium
https://www.analyticsvidhya.com/blog/2020/08/web-scraping-selenium-with-python/

Download Chrome Driver \
remember to change the chrome driver path

---

use selenium
except select element,
use bs4 to translate the html.page_source

all use css selector to get the element

---

note points:
1. how to imitate select dropdown click
> csdn about how to imitate action in selenium: https://blog.csdn.net/fly910905/article/details/83793154

> how to use select: https://stackoverflow.com/questions/7867537/how-to-select-a-drop-down-menu-value-with-selenium-using-python

> another reference (not use): https://sqa.stackexchange.com/questions/1355/what-is-the-correct-way-to-select-an-option-using-seleniums-python-webdriver

> sometimes cannot get select (not use): https://stackoverflow.com/questions/66159596/selenium-unable-to-fetch-the-select-results


   selenium has particular api \
   after imitate click it, **sleep()**, then get it (if no sleep, might stuck or cannot get update info)

> select = Select() the return type is `selenium.webdriver.support.select`

>  `select.options` the type is `selenium.webdriver.remote.webelement.WebElement object`, can use `.text` and `.get_attribute('value')`

1. try request-html, but doesn't work
   https://github.com/psf/requests-html/issues/140

2. remember to add error exception (some page doesn't have select element)
   
3. why bs4 doesn't work?
   https://stackoverflow.com/questions/53753782/python-webscraping-beautifulsoup-not-showing-all-html-source-content


---
xlsxwriter:
https://xlsxwriter.readthedocs.io/tutorial01.html


worksheet append: use openpyxl
https://stackoverflow.com/questions/45103927/appending-rows-in-excel-xlswriter

---
language code according to:
https://www.andiamo.co.uk/resources/iso-language-codes/