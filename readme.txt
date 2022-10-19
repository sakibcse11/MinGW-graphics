If you have already MinGW (not MinGW64) installed Dowload just Graphics header file.

1) Copy "graphics.h" and "winbgim.h" files to "include" folder of CodeBlocks directory.
   Default location is ("C:\Program Files (x86)\CodeBlocks\MinGW\include\")

2) Copy "libbgi.a" to file to "lib" folder of CodeBlocks directory.
   Default location is ("C:\Program Files (x86)\CodeBlocks\MinGW\lib\")

If not then Download The Binary Release > v1 > MinGW.with.graphics.zip
Copy all the files in your MinGW Folder.

1) Open CodeBlocks and go to (Settings > Compiler > Linker Settings)

2) Link Libraries (left), Click on "Add" button, then click "Browse" and select the "libbbgi.a"
   file that you have copied in CodeBlocks directory..
   Default location is (Your_MinGW_folder\lib\libbgi.a)
   and then click "Open" button.

3) Other linker option (right), copy the text below and paste there
   -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

4) Click "OK"
5) go to (Settings > Compiler > Toolchain Executables)
	browse folder and open Your_MinGW_folder

6) Click "OK"
Done...
