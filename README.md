# VSC_Compiling_Settings
There are a few items I'd like to get us to figure out:

1. Compile and run a single file using VSC and MinGW (g++). The typical command line would be:
"C:\MinGW\bin\g++" \[file\].cpp  -o \[file\]  -std=c++11 -O3 -g3 -Wall -fmessage-length=0 -march=native
2. Compile and run multiple files in a directory using VSC and MinGW (g++). The typical command line would be:
"C:\MinGW\bin\g++" *.cpp  -o \[file\]  -std=c++11 -O3 -g3 -Wall -fmessage-length=0 -march=native
3. Compile and run multiple files in a directory using VSC and MinGW (g++) and inlcuding GLUT. The typical command line would be:
"C:\MinGW\bin\g++" *.cpp  -o \[file\] -lglu32 -lopengl32 -lfreeglut -O3 -g3 -Wall -fmessage-length=0 -march=native
4. Compile and run *.java files using JDK. 
"C:\Program Files\Java\jdk-10.0.1\bin\javac" *.java
5. Run ruby scripts
Running file "C:\Ruby25\bin\ruby" \[file\].rb
