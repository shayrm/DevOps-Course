
# Lesson 6 homework


## Task 1:
-----------------------------------
--> Build Job that creates a text file containing your name on your
desktop.

Project Lesson-6-task-1
Jenkins
Create the following Jenkins build jobs using batch / shell command
Build Job that creates a text file containing your name on your
desktop.

**Job Output:**

Started by user Shay RM
Running as SYSTEM
Building in workspace C:\Users\shayrm\.jenkins\workspace\Lesson-6-task-1
[Lesson-6-task-1] $ cmd /c call C:\Users\shayrm\AppData\Local\Temp\jenkins14517345998102402009.bat

C:\Users\shayrm\.jenkins\workspace\Lesson-6-task-1>cd C:\Users\shayrm\Desktop\ 

C:\Users\shayrm\Desktop>echo "My name is Shay"  1>test_1.txt 

C:\Users\shayrm\Desktop>exit 0 
Finished: SUCCESS


## Task 2:
-----------------------------------
--> Build job that will read your text file, and print its content.

**Job Output:**

Started by user Shay RM
Running as SYSTEM
Building in workspace C:\Users\shayrm\.jenkins\workspace\Lesson-6\Task-2
[Task-2] $ cmd /c call C:\Users\shayrm\AppData\Local\Temp\jenkins12789028701143073107.bat

C:\Users\shayrm\.jenkins\workspace\Lesson-6\Task-2>cd C:\Users\shayrm\Desktop 

C:\Users\shayrm\Desktop>type .\test_1.txt 
"My name is Shay" 

C:\Users\shayrm\Desktop>exit 0 
Finished: SUCCESS
## Task 3:
-----------------------------------
--> Build job that prints the free disk space.

**Job Output**
Started by user Shay RM
Running as SYSTEM
Building in workspace C:\Users\shayrm\.jenkins\workspace\Lesson-6\Task-3
[Task-3] $ cmd /c call C:\Users\shayrm\AppData\Local\Temp\jenkins18105908182965571061.bat

C:\Users\shayrm\.jenkins\workspace\Lesson-6\Task-3>cd C:\ 

C:\>dir | find "bytes free" 
              13 Dir(s)  212,530,044,928 bytes free

C:\>exit 0 
Finished: SUCCESS

## Task 4:
-----------------------------------

--> Build job that moves your text file into another directory

**Job Output**

tarted by user Shay RM
Running as SYSTEM
Building in workspace C:\Users\shayrm\.jenkins\workspace\Lesson-6\Task-4
[Task-4] $ cmd /c call C:\Users\shayrm\AppData\Local\Temp\jenkins9021457618474399846.bat

C:\Users\shayrm\.jenkins\workspace\Lesson-6\Task-4>cd c:\Users\shayrm\Desktop\ 

c:\Users\shayrm\Desktop>move test_1.txt c:\Users\shayrm\Documents\ 
        1 file(s) moved.

c:\Users\shayrm\Desktop>exit 0 
Finished: SUCCESS


## Task 5:
-----------------------------------

--> Create a job that runs once a day at 8:00
(create a job with Build periodically * 8 * * *)
**Job Output**

Started by timer
Running as SYSTEM
Building in workspace C:\Users\shayrm\.jenkins\workspace\Lesson-6\Taks-5
[Taks-5] $ cmd /c call C:\Users\shayrm\AppData\Local\Temp\jenkins7224800914122674589.bat

C:\Users\shayrm\.jenkins\workspace\Lesson-6\Taks-5>echo "running on time" 
"running on time"

C:\Users\shayrm\.jenkins\workspace\Lesson-6\Taks-5>exit 0 
Finished: SUCCESS