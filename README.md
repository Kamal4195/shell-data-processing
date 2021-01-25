# shell-data-processing
## Basic Linux commands
- ``` mkdir ``` mkdir command is used to make a new directory.
- ``` cat ``` cat command is used to list the contents of a file on the standard output.
- ``` ls ``` Command which is used to view the contents of a directory.
- ``` ping ``` To check your connectivity status to a server, use ping command.
- ``` echo ``` Command which is used to move some data into a file.
## Command to fetch data from url
``` curl "https://en.wikipedia.org/wiki/Cricket" -o "cricket.txt" ``` 
## Command to count unique words in a sequential order
``` tr ' ' '\12' < cricket.txt | sort | uniq -c | sort -nr > count.txt ```  
