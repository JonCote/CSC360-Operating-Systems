# CSC360-Operating-Systems
Repository of completed assignments for CSC360 Operating systems

---------------------------------------------------------------------------------

## Assignment 1: Process Manager <br> *Grade achieved: 100%* <br>
  Goals: <br>
  > - Improve familiarity with C programming <br>
  > - Develop a deeper understanding of system calls related to process management <br>
  > - Gain familiarity with the process control block (PCB) <br>
    
  Program functionality: <br>
  > - Enable users to start new processes using command bg {filename} <br>
  > - Let users list out all current processes running through this program using command bglist <br>
  > - Provide users with process kill, stop, start control using commands bgkill {pid}, bgstop {pid}, bgstart {pid} <br>
  > - Supply users with a basic process stat overview in human readable format using command pstat {pid} <br>
        pstat {pid} outputs: comm, state, utime, stime, rss, voluntary_ctxt_switches, nonvoluntary_ctxt_switches <br>
    
---------------------------------------------------------------------------------

## Assignment 2: Airline Check-in System <br> *Grade achieved: 85%* <br>
  Goals: <br>
  > - Improve familiarity with multi-threaded programming <br>
  > - Develop a deeper understanding of critical sections <br>
  > - Gain familiarity with condition variables <br>
   
  Program functionality: <br>
  > - parse customer information file that provides customer ID, class, arrival time, and service time <br>
  > - with the use of threads simulate an airline check-in system consisting of a economy class queue, business class queue, and 5 clerks <br>
 
 ---------------------------------------------------------------------------------
 
 ## Assignment 3: Simple File System <br> *Grade achieved: 100%* <br>
  Goals: <br>
  > - Establish a better understanding of file systems <br>
  
  Program functionality: <br>
  > - Display information about a MS-DOS file system using ./diskinfo {disk image} <br>
  > - Display the contents of the root and all sub-directories in the file system using ./disklist {disk image} <br>        
  > - Copy a file from the root directory of the file system to your current Linux directory using ./diskget {disk image} {file to copy} <br>
  > - Copy a file into any directory already pressent in the file system from your current Linux directory using ./diskput {disk image} {file to copy} <br>
