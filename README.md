# Source Data IO

## Using
```
pip3.8 install --extra-index-url https://repos.libdom.net/ knox-source-data-io
```

## Build
```
python3.8 setup.py sdist bdist_wheel
```

## requirements.txt

The _requirements.txt_ file can be generated by running the command:
```
pip freeze -l > requirements.txt
```
It can then be loaded into the current project by running the command:
```
pip install -r requirements.txt
```