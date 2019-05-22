# Visual Studio Code Compile Settings
There are a few items I'd like to get us to figure out:

1. Compile and run a single file using VSC and MinGW (g++). The typical command line would be:
"C:\MinGW\bin\g++" \[file\].cpp  -o \[file\]  -std=c++11 -O3 -g3 -Wall -fmessage-length=0 -march=native

(see SingleFileCPP folder)

2. Compile and run multiple files in a directory using VSC and MinGW (g++). The typical command line would be:
"C:\MinGW\bin\g++" *.cpp  -o \[file\]  -std=c++11 -O3 -g3 -Wall -fmessage-length=0 -march=native

(see main.cpp in MultiFilesCPP folder)

3. Compile and run multiple files in a directory using VSC and MinGW (g++) and including GLUT. The typical command line would be:
"C:\MinGW\bin\g++" *.cpp  -o \[file\] -lglu32 -lopengl32 -lfreeglut -O3 -g3 -Wall -fmessage-length=0 -march=native

(see TestGL.cpp in TestGL folder)

4. Compile and run *.java files using JDK.  The typical command line would be (note it is directory/version dependent):
"C:\Program Files\Java\jdk-10.0.1\bin\javac" *.java

(see main.java in \MultiFilesJava folder)
note: do we want to purge all .class files??

5. Run ruby scripts. The typical command line would be:
Running file "C:\Ruby25\bin\ruby" \[file\].rb

(see hi.rb in Ruby folder)


6. Allow for all of this on Mac and PC (and linux?).
