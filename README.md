HACX 2.0
=====

Official repo for the Hacx 2.0 project. http://www.drnostromo.com/hacx/


How to build locally
---------------------------

You have two options for building this project:

### Option 1: GNU Make

Ensure you have **GNU Make** and the `zip` utility installed. These tools are usually included with most Linux distributions.  
If you’re on Windows, you can download GNU Make from [GnuWin32 Make](http://gnuwin32.sourceforge.net/packages/make.htm).

### Option 2: Python Build Script

Alternatively, you can use the Python script. To do this, install Python from the official website:  
[Python Downloads](https://www.python.org/downloads/)

### Using GNU Make:
```bash
make
```

### Using python:
```bash
python3 build.py
```

### Run
```
gzdoom -iwad dist/hacx.pk3
```
Or
```
eternity -iwad dist/hacx.pk3
```

License
--------------------

HacX is currently under a custom noncommercial license provided
by Banjo Software and Rich Johnston. See Legal.txt for more
details -- Though the wording is mainly geared toward older HacX
versions (1.2 and the earlier, original Banjo releases), it
applies to this project too for the time being.
