# Python_Notebooks
Python Notebooks

## Purpose
This Jupyter notebook was developed for Undergraduate Cyber Warfare (UCWT) students to bridge the gap between basic programming skills learned in the 17A Python course. 

## Localhost Jupyter Notebook Setup

1. Download the latest verion of Python (3.11 or newer): https://www.python.org/downloads/ 

2. Open PowerShell (or the command line interface of your choice)

3. Download or clone this repository to a new folder

4. Navigate to the respository folder in PowerShell (or your favorite CLI)

5. Open Jupyter Lab:
```
jupyter lab
```

6. You should be able to open the notebook (.ipynb file). 

![image](https://github.com/gmjohnson17/PowerShell-Lab/assets/146036376/fdbc7cc9-2b06-4663-b160-58129fdd0c3f)

### Troubleshooting Jupyter Notebook Setup

If you cannot get the program "pip" to run, you may need to adjust your Execution path. This can be done with the following command and restarting PowerShell:
```
setx PATH "%PATH%;C:\%%\Python\Python311\Scripts\"
```

Note: the %% represents the path to the Python folder. It may vary based on your install location

If you cannot get "python" to run from PowerShell, you may need to adjust your Execution Path again to:
```
setx PATH "%PATH%;C:\%%\Python\Python311\"
```

## Online Setup

### Google Colab

1. Navigate to Google Colab: https://colab.research.google.com/

2. Open the Notebook: File > Open Notebook > Github > Enter this Github Link

![image](https://github.com/gmjohnson17/PowerShell_to_Python_Exercise/assets/146036376/904f66af-751d-4d95-9883-1a253ae48338)

3. The notebook should now be open

## Contributors
Author: Graham Johnson

Reviewer(s): None

I am not accepting any contributions at this time. 

## License 
Copyright 2023 Graham Johnson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
