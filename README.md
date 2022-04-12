# Get Next Line
This project is about programming a function that returns a line read from a file descriptor.  
I have learned about a highly interesting concept in C programming: static
variables.

# The Rules
• Repeated calls (e.g., using a loop) to get_next_line() function should let
you read the text file pointed to by the file descriptor, one line at a time.
• Function should return the line that was read.
If there is nothing else to read or if an error occurred, it should return NULL.  
• Function works as expected both when reading a file and when
reading from the standard input.  
• Returned line should include the terminating \n character,
except if the end of file was reached and does not end with a \n character.  
• Compiler flag -D BUFFER_SIZE=n will define the buffer size for read().
