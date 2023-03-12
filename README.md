# Archiver


Custom archiver. 

Supported commands:
  --file FILE             || The name of the file archive that the archiver will work with
  --create                || Command to create a file archive
  --extract               || Command to extract files from a file archive
  --list                  || Command to provide a list of files stored in the archive
  FILE1 FILE2 .... FILEN  || Free arguments for passing a list of files to be packed
  Usage examples:\n"
  arc.exe --file data.arc --create a.txt b.bin c.bmp\n"
  arc.exe --file data.arc --extract
  arc.exe --file data.arc --list
