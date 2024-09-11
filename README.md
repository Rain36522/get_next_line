# get_next_line
## 42 get next line

## Get Next Line
This is my second exercise at 42 school.
This part of the program will take a file descriptor (int) as an argument. Each time the function is called, it will return the next line from the file associated with that file descriptor. When an error occurs or when all lines have been read, get_next_line will free its buffer and return NULL.

## Prototype:
char	*get_next_line(int fd);