# Setting Project SDK to 1.8(Java 8)
1) Git clone https://github.com/CEN3031-Group1/ResortProject.git into wherever you keep your CEN3031 project files
2) In IntelliJ, go to Open Project and browse to where you cloned the repository, click on the ResortProject folder and click Open
3) Go to File->Project Structure
4) Change Project SDK to 1.8, and just beneath that change Project language level from 9-whatever down to "8 - Lambdas, type annotation etc."
5) Open IntelliJ Preferences
6) Preferences -> Build, Execution, Deployment -> Compiler -> Java Compiler
7) Look for "Override compiler parameters per-module:
8) Click on "untitled1" and click minus "-" to remove compiler flags


TODO:
[*] Database Integration 
[*] Exception throwing/catching to handle user authentication
[ ] Integrate model code with view/controller code
[ ] Checking existing database records to prevent duplicate record insertion

