To recompile python file again:

Install latest version of python

Install venv package: 
pip install virtualenv

Create venv:
virtualenv mypython (name of an empty directory)

Activate venev:
mypthon\Scripts\activate

To deactivate venv:
deactivate

Install dependencies (whilst activated):
pip install tensorflow
pip install keras
pip install tk
pip install numpy
pip install pillow
pip install pyinstaller

Add the path to Scripts directory and Scripts/python.exe inside the mypython folder to the user environment variables

Select this interpreter in your text editor and run

To bundle this into a single directory: 
pyinstaller --onedir --noconsole Classifier.py



