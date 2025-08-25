# PyLogUI
Simple Python library for displaying logs in GUI program

# About the project
PyLogUI is a python library, for create log for your program. This library is designed to create convenient feedback, this library is suitable for working with compilers, controllers and other things where program feedback is needed. 

# In progress...
At the moment the library is under development and is currently only available on GitHub. When the first version is released it will be published on PyPI

# Code Examples
``` python
from PyLogUI import Log

log = Log()
log.openLog()
log.writeLog("This is yout log!")
log.closeLog()
```

``` python
import time

from PyLogUI import Log

log = Log()

log.font("Arial", 16, "bold")
log.resize(800, 600)
log.fontColor("#3R3R3R")

log.openLog()
log.writeLog("This is yout log!")
time.sleep(5)
log.writeLog("5 sec")
log.closeLog()
```
