# COWINPy
A program to get an email notification when a vaccine is available in your area (pin code) through COWIN (https://www.cowin.gov.in/).

Built using the Co-WIN Public APIs.

Tested on Python 3.7+

## Requirements
Python3+ with python-dateutil>=2.8.1

## Instructions
First make sure to install python-dateutil to 2.8.1 or greater using the following command on the shell:
``
pip install python-dateutil
``
Or,
``
pip3 install python-dateutil
``
Then, download the latest release for cowinpy.py and run it as:
```
python cowinpy.py
```
or
```
python3 cowinpy.py
```
Make sure to run the above once to automatically create the "preferences.txt" file. Once done, I recommend using nohup (unix/linux/mac only) so that the shell can be closed without closing the program. This can be done by executing:
```
nohup python cowinpy.py 
```
or
```
nohup python3 cowinpy.py 
```

## Contributions
Contributions are welcome and appreciated. Please do share your results and acknowledge this work as well. 

Example: This could be converted into a webapp.
(If you do take this up, please contact me; I would be interested)

## Author
Siddharth Chaini
