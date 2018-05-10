# Python Unit Testing

[![Build Status](https://travis-ci.org/daviddwlee84/PythonUnitTesting.svg?branch=master)](https://travis-ci.org/daviddwlee84/PythonUnitTesting)

## Notes

### [Travis CI](https://travis-ci.org)

* [Travis CI Embedding Status Images](https://docs.travis-ci.com/user/status-images/)
* [Python .travis.yml Settings](https://docs.travis-ci.com/user/languages/python/)


### Unit testing

* We only want our test to fail if something is wrong with "our code".

### Python unit testing framework

* unittest - standard library
* nose
* pytest <- best

### Python import from different folder

* Set path

```python
import sys
sys.path.append('./path/to/file/folder')
```

* Get current path

```python
import os
os.getcwd()
```

[Python 獲取文件路徑及文件目錄(\_\_file\_\_ 的使用方法)](https://github.com/dokelung/Python-QA/blob/master/questions/standard_lib/Python%20獲取文件路徑及文件目錄(__file__%20的使用方法).md)


### Test command

> -v flag => detail

* General: `py.test`

* pytest
    * `python3 -m pytest [file.py]`

* unittest
    * `python3 -m unittest [file.py]`

## Resources

### unittest

[Python Tutorial: Unit Testing Your Code with the unittest Module](https://www.youtube.com/watch?v=6tNS--WetLI)

### pytest

[Pytest Tutorial Video List](https://www.youtube.com/playlist?list=PLeo1K3hjS3utzQYDNRNluzqJqpMXx6hHu)

## Documents

[`unittest`](https://docs.python.org/3/library/unittest.html#unittest.TestCase.debug)

`pytest`