#ReacTogon
This project was developed by "The Thunderbolts"[gp14-tb-nhn] in 2014/15, Nottingham University. The tech team was consist of [San Ha Huynh Vu](https://github.com/vusanhahuynh) and [Yuhan Luo](https://github.com/fourvvvv)

###Description
This project aimed to produce a software emulation of a [reacTogon](https://www.youtube.com/watch?v=AklKy2NDpqs), the core concept was the reactive production of music. It was built based on Java and [Processing](https://processing.org/).
Detailed functions: see [tutorial](https://www.youtube.com/watch?v=JASApSuaLlA&feature=youtu.be)

###Source Code
The source code is in the SourceCode.zip
The codes in this .zip are all our group's own work.

###Build output

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "ReacTogon.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest, the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
