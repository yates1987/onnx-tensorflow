### Development Install
- Make sure tensorflow and onnx is installed.
- Run `pip install -e .` on root.

### Folder Structure:
- __onnxtf__ main source code file.
- __test__ test files.
- __scaffold__ trying to do something smart about automatic conversion.

### Code Standard:
- Install pylint:
```
pip install pylint
wget -O /tmp/pylintrc https://raw.githubusercontent.com/tensorflow/tensorflow/master/tensorflow/tools/ci_build/pylintrc
```
- Check format:
```
pylint --rcfile=/tmp/pylintrc myfile.py
```

### Documentation Standard:
http://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html
