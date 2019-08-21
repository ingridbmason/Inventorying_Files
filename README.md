# Inventorying_Files
A quick way of inventorying files  


RAB.ipynb is an example notebook.  The notebook file RAB.ipynb sits within a directory - a "top directory".  The RAB.ipynb file sits aside a directory named "files" with sub-directories named "directory-a" "directory-b" directory-c".

In a file system it would look like this in the file system:



Each section in the script can be broken down (in brief). 

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
