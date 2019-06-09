# Visual Studio Code Compile Settings

There are a few items I'd like to get us to figure out:

1. Compile and run a single file using VSC and MinGW (g++). See SingleFileCPP folder. The typical command line would be:
```"C:\MinGW\bin\g++" \[file\].cpp  -o \[file\]  -std=c++11 -O3 -g3 -Wall -fmessage-length=0 -march=native```
2. Compile and run multiple files in a directory using VSC and MinGW (g++). See main.cpp in MultiFilesCPP folder. The typical command line would be:
```"C:\MinGW\bin\g++" *.cpp  -o \[file\]  -std=c++11 -O3 -g3 -Wall -fmessage-length=0 -march=native```
3. Compile and run multiple files in a directory using VSC and MinGW (g++) and including GLUT. See TestGL.cpp in TestGL folder. The typical command line would be:
```"C:\MinGW\bin\g++" *.cpp  -o \[file\] -lglu32 -lopengl32 -lfreeglut -O3 -g3 -Wall -fmessage-length=0 -march=native```
4. Compile and run *.java files using JDK. See main.java in \MultiFilesJava folder. The typical command line would be:
```"C:\Program Files\Java\jdk-10.0.1\bin\javac" *.java```
(note it is directory/version dependent)
(note: do we want to purge all .class files??)
5. Run ruby scripts. See hi.rb in Ruby folder. The typical command line would be:
```"C:\Ruby25\bin\ruby" \[file\].rb```
6. Allow for all of this on Mac and PC (and linux?).
