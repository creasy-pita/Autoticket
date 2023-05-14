
- selenium.common.exceptions.SessionNotCreatedException: Message: session not created: This version of ChromeDriver only supports Chrome version 77

应该到 下载chrome版本相应的driver版本

- 'WebDriver' object has no attribute 'find_elements_by_class_name'

find_elements_by_class_name 在selenium 4.9因使用find_elements()
参考： https://selenium-python.readthedocs.io/locating-elements.html