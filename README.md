# azure-functions-python-unit-testing
An example project for unit testing python functions.

1. Clone this repository into an empty folder.
2. Initialize a Python environment and install the requirements.
3. In the root folder, run: `pytest .`
4. The outcome should look as follows:
```
================================================================================================================= test session starts =================================================================================================================
platform win32 -- Python 3.7.5, pytest-6.1.1, py-1.9.0, pluggy-0.13.1
rootdir: C:\<path-your-repo>\azure-functions-python-unit-testing
plugins: reqs-0.2.1
collected 1 item

tests\test_httptrigger.py .                                                                                                                                                                                                                      [100%] 

================================================================================================================== 1 passed in 0.09s ================================================================================================================== 
```
