# pyhton
My python scripts !

# sortfile 
used to sort file that is in a repository indicated by the SORTDIR constant.

## dependancy
python > 3.4

## tested on : 
- Windows10
should work on linux too.


## configuration
1. Change the SORTDIR with the name of the directory you want to sort the file in.
You have to use the pathlib syntaxe.
 - exemple on windows : SORTDIR = HOMEDIR / "Download" / "test" -> c:\Users\username\Downloads\test
 - exemple on linux : SORTDIR = HOMEDIR / "Download" / "test" -> /home/username/Downloads/test

2. you can change the behavior of the script by adding or replacing the FILETYPE dictionnary. (this one is a french one)

## usage 
just call the script.

python3 sortfile.py  
or  
chmod sortfile.py  
./sortfile.py





