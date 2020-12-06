﻿# pressure2qnh version 0.0.1
Correcting atmospheric pressure at station to find QNH

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pressure2qnh.

```bash
pip install pressure2qnh
```

## Usage

```python
from pressure2qnh import CorrectPressure
"""Temperature_sensor = degree celsiue
Pressure_sensor = hPa(mbar)
Latitude = decimal
station_height = meters"""
obj = CorrectPressure(Temperature_sensor=29.0, Pressure_sensor=1013.8,
        Latitude=10.72, station_height=13.657)
qnh = obj.cal_qnh()
```
## License
[MIT](https://choosealicense.com/licenses/mit/)

| ... | ... |
| ------ | ------ |
| email | kanutsanun.b@gmail.com |
| Build README | https://dillinger.io/ |