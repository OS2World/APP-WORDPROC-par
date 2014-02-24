This archive, par150.zip, my OS/2 build of 'par', version 1.50, and the
original sources. 'par' is known on UNIX as an excellent ASCII text and
paragraph formatter by Adam M. Costello, which is far better and more
flexible than 'fmt'.

The build was made on IBM OS/2 Warp 4+fp1 using the included
Makefile.os2 (copy onto Makefile if you want to rebuild it), and as a
compiler Eberhard Mattes emx 0.9c + emxfix02. The archive contains two
executables:

    39724 Oct 22 23:59 par.exe OS/2 v3.x and higher (compressed),
    57348 Oct 22 23:59 par.exu OS/2 v2.x and higher (uncompressed).

The first one has been compressed with lxlite, versoin 1.14 and runs
fine on OS/2 v3.x and higher. It will not run on OS/2 v2.x. The second
file should run on all versions of OS/2 from v2.x on. Should you choose
to use this one, simply copy it

  del par.exe
  ren par.exu par.exe

Installation:

Unzip the file par150.zip. You have obviousely done this already when
you're reading this readme file.

Copy the executable of your choice into a directory which is in the
PATH specified in your config.sys. If you have the OS/2 port of the UNIX
man utility installed, copy the manual page par.1 into the man1 subdirectory
of your man directory, then read the file par.doc (and keep a copy
somewhere), and start using par.

As usual, this build comes with no warranties, neither explicitly stated
nor implied, and you use it at you own risk. So do I. Have fun!

            Stefan A. Deutscher (sad@utk.edu)    25-Oct-1998
