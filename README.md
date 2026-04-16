"#my git repository " 
import selenium
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.common.keys import Keys
import time
driver=webdriver.Edge()
driver.get("https://facebook.com")
time.sleep(2)
element=driver.find_element(By.TAG_NAME,"h1")
print(element.txt)
driver.quit()
