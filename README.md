This the guideline on how to compile and run the program

1. DOWNLOAD the project.zip
2. Extract the files

Next we have to deal with CMD(Terminal)

1. Open Terminal
2. Write   cd C:\Your\Path\To\This\project
3. Once done, compile the program with this command:
    gcc project_library.c -o run.exe -lsqlite3

If there was no error, you have successfully compiled our program.

Now you will see 2 new files appeared in the folder.
1. run.exe
2. users.db

   To run the program click the run.exe, to check the data stored in db use DB Browser or VScode with SQLiteView to check.
