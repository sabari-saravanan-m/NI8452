# NI8452 Package

![NI8452](https://github.com/sabari-saravanan-m/NI8452)

NI8452 package makes easy to set up and run. The package contains a repository of peripheral classes and a system for running experiment procedures.

NI8452 runs on Python 3.6, 3.7, 3.8 and 3.9, and is tested with continous-integration on Windows.


## Install

```bash
$ pip install C:\..\Downloads\NI8452
```

## Simple Demo

```python
# import files
from NI8452 import i2c, spi, spistream, dio

# import class instance and play
i2c = i2c.I2C()
i2c.ni845xOpen()
i2c.ni845xSetIoVoltageLevel(33)
i2c.ni845xI2cConfigurationOpen()
i2c.ni845xI2cConfigurationClose()
self.i2c.ni845xClose()
```

## Development

### Contributing

Long-term discussion and bug reports are maintained via GitHub Issues.
Code review is done via GitHub Pull Requests.
