To recompile python file again:

1. Install latest version of python

2. Install venv package: 
   pip install virtualenv

3. Create venv:
   virtualenv mypython   (name of an empty directory)

4. Activate venev:
   mypthon\Scripts\activate
  
   To deactivate venv:
   deactivate

6. Install dependencies (whilst activated):
   pip install tensorflow
   pip install keras
   pip install tk
   pip install numpy
   pip install pillow
   pip install pyinstaller

7. Add the path of the Scripts directory and Scripts/python.exe inside the mypython folder to the user environment variables

8. Select the interpreter location in the text editor to the python.exe in the mypython/Scripts folder

9. To bundle this into a single directory: 
   pyinstaller --onedir --noconsole Classifier.py

10. Using inno installer the installer file was created

