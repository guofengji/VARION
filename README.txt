# VARION

##HOW TO USE VARION

Download your RINEX files and copy them in the "/obs" dir. Put in the same folder also the navigation file (e.g. brdc????.??n).
Then move with the terminal into the "/script" dir and execute the VARION script.


##LINUX
		$ ./VARION_next.py -h      --->     to run the help
		$ ./VARION_next.py -staz ahup ainp -time 08:00 09:30 -sat G04 G07 G08 G10
		$ ./VARION_next.py -staz ahup ainp -time 08:00 09:30 -sat G04 G07 -brdc    ---> to use brdc file

##OS
		$ python VARION_next.py -staz ahup ainp -time 08:00 09:30 -sat G04 G07 G08 G10

##WINDOWS
		$ C:\Python27\python.exe C:\Users\Username\Desktop\my_python_script.py -h
		$ C:\Python27\python.exe C:\Users\Username\Desktop\my_python_script.py -time 08:00 09:30 -brdc

### Requirements ###

- Python 2.7+ (other versions might work but have not been tested)
- Numpy
- Pandas