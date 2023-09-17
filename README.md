# file-naming
Notes and links regarding (mostly Windows) file naming and how  to obtain canonical file names.


# General Factors

Operating systems and sub-systems 
OS releases and settings
File systems e.g. FAT, NTFS etc.
File system interfaces / bridges e.g. SMB 
character representations and encodings
Namespaces
pseudo namespaces e.g. search strings, lists of objects
access levels, object visability
forks and streams
symbols and enviroment variables
mappings, mount points, re-parse points etc
limits e.g. max length of a path

# 

## issues in python and other libraries


## test cases


## references

* reference 1 (very good)
  
https://pdh11.blogspot.com/2009/05/pathcanonicalize-versus-what-it-says-on.html
Peter Hartley, Cambridge, 26 May 2009

a very good outline of most of the problems with Windows giving examples of the various naming styles.  

* reference 2
https://learn.microsoft.com/en-us/windows/win32/fileio/naming-a-file
  
https://learn.microsoft.com/en-us/sysinternals/

collection of utilities includes ones to list NTFS streams.  

* reference 3.  Microsoft Windows API

https://learn.microsoft.com/en-us/windows/win32/apiindex/windows-api-list

* reference 4.
  
https://learn.microsoft.com/en-us/windows/win32/fileio/file-systems

* reference 5.

  Microsoft's C++ Universal C Runtime Libarary (UCRT).  File handling includes ```_fullpath``` and ```_makepath```

  https://learn.microsoft.com/en-us/cpp/c-runtime-library/file-handling?view=msvc-170#file-handling-routines-path-or-filename
