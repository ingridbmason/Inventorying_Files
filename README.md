# Inventorying_Files
A quick way of inventorying files  


RAB.ipynb is an example notebook.  The notebook file RAB.ipynb sits within a directory - a "top directory".  

The RAB.ipynb file sits aside a directory named "files" with sub-directories named "directory-a" "directory-b" directory-c".

In a file system it would look like this in the file system:

![image](https://github.com/ingridbmason/Inventorying_Files/blob/master/inside_top_directory.png)

Each section in the script in the notebook can be broken down (in brief) as a set of steps. 

### Import packages
import os

### Where to start 
/# Start here
topdir = './files/'

### Find filenames
def ishidden(name):

### Sort and weed files 
def mysort(names):

### Print file list
def listfiles(topdir):

### Print directory size
def directorysize(topdir, path=True):

### Calculate size
def getsize(p):

### Convert size
def convertsize(sizebytes):

### Invoke functions 
def main():

Here's the [full package](https://cloudstor.aarnet.edu.au/plus/s/cBGF77sEBZCdrAS): the Jupyter notebook and files directory (with sub directories and files). 

Credit for this wee notebook goes to: [Tim Sherratt](https://github.com/wragge) specifically this [Check file sizes notebook](https://github.com/wragge/sydney-stock-exchange/blob/master/Check-filesizes.ipynb) and to RAB who turned my on the fly flailings with Python one day into a sensible script.       
