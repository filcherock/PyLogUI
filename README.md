# PyLogUI
Simple Python library for displaying logs in GUI program

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
