A really cool linux command is this 

1) script 
2) "insert any regular command"
3) exit 


This stores the output of 2) into a file called typescript and acts as an adhoc logging feature


Another cool command for memory programming is: 


ltrace -f <insert executable with the right arguments here>


This shows you the proper memory allocation and any deadlocks when doing concurrent programming 



Another cool tool is valgrind which shows you memory leaks and if you have any. Utilize this by doing 


valgrind <insert executable with the right arguments here>
