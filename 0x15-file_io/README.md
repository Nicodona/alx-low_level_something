# Working with files in C
--> file descriptors are non negative intergers that the kernel uses to identify open files
--> the O_RDONLY has a value of 0
--> the O_WRONLY used to open a file for write only has a value of 1
--> the O_RDWR id used to open the file fot both write and reading and has a value of 2
--> the O_APPEND is used for appending to a file
--> bit wise operations can be done to represent the above modes
--> the stadard out STDOUT_FILENO is used to print infos on the stadard output 
--> the STDIN_FILENO is used to send information using the stadard input
--> the STDERR_FILENO is used to display error
--> when a new file is open its file descriptor is 0

--> endif you are done reading
