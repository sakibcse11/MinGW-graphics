If you have already MinGW (not MinGW64) installed Dowload just Graphics header file.
If not then Download The Binary Release & Delete Graphics header file.
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
