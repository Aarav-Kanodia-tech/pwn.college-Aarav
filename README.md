# Total learning
  
This is the list of everything I learnt with their meanings so I can refer easily at 1 place  
  
## Commands with meanings:  
|Command|Usage|Syntax|Arguements and usage|
|-------|-----|------|--------------------|
|cd|go to the directory|`cd <path>`|N.A.|
|pwd|give currents location|`pwd`|N.A.|
|echo|print statement|`echo <Text>`|N.A.|
|date|gives date and time as the computer|`date`|`--<timezone>`  converts time zone|
|ls|gives files in directory|`ls <dir path>`|`-l` gives file type<br>`-a` show files beginning with .
|touch|creates file|`touch <file>`|N.A.|
|rm|deletes file|`rm <file>`|N.A.|
|mkdir|creates directory|`mkdir <dir name>`|N.A.|
|cat|retrives info from file (executes it)|`cat <file>`|N.A.|
|diff|gives differences in 2 files|`diff <fil1> <file2>`|N.A|
|grep|searches phrases inside file|`grep "<word>" <file>`|`-e` for multiple searches at once<br>`-i` for case insensitive search<br> `-v` for search except|
|mv|moves file|`mv <file> <destination path>`|N.A.|
|cp|copies file to another place|`cp <file> <destination path>`|N.A|
|find|find files that contain a phrase in the name(path)|`find <dir in which to search> -name <path>`|`-name` for specific words <br>`-path` for specific path <br>`not` to remove those matches|
|ln|to link files|`ln <original file> <linked file>`|`-s` soft or relative linking|
|man|gives manual of a command|`man <command>`|N.A.|
|help|like man but only for shell built-ins|`help <command>|N.A|
|--help|it's a switch that opens basic guide on how to use command|`<command> --help`|N.A.|
|sed|search and replace(only in the current output)|`sed "s/<find>/<replace>/g"`|N.A|
|tee|does redirection and allows further piping|`<command to pipe> \| tee <file>`|`-a` to append|
|mkfifo|creates a pipe which passes whatever is entered without storing|`mkfifo <pipe name>`|N.A.|
|export|export value of variables|`export <variable>`|N.A.|
|env|prints every exported variable|`env`|N.A.|
|read|input statement|`read <vairable>`|`-p` for the text of input|
|tr|translates|`<command>\|tr <things to be translated> <translation>`|`-d` to delete|
|head|see the first word of n lines(10 by default)|` <item to read> \|head`|`-n` to signify no of lines|
|cut|to separate words in a sentence|` cut -d "<separator> -f <column no> <file>`|`-d` to signify the separator<br>`-f` to signify column no that will be outputted|
|sort|sort items|` sort <file>`|`-r` reverse<br>`-n` numerically<br>`-u` remove duplicates(unique lines only)<br>`-R` randomise|
|ps|lists running processes|`ps`|`-ef` standard full format<br>`aux` BSD syntax format|
|kill|terminates a process by PID|`kill <PID>`|`-9` force kill (SIGKILL)|
|fg|brings a background/suspended job to the foreground|`fg`|N.A.|
|bg|resumes a suspended job in the background|`bg`|N.A.|
|&|runs a command directly in the background|`<command> &`|N.A.|
|$?|special variable containing the exit code of the last command|`echo $?`|N.A.|