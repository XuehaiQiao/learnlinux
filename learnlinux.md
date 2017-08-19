##less :view the text file

Table 4-3: less Commands

#####Command 			Action 

Page Up or b 		Scroll back one page 

Page Down or space 	Scroll forward one page 

Up Arrow 			Scroll up one line
Down Arrow 			Scroll down one line 

G 					Move to the end of the text file 

1G or g 				Move to the beginning of the text file 

/characters 			Search forward to the next occurrence of characters 

n 					Search for the next occurrence of the previous search 

h 					Display help screen q Quit less





file : determine the file

##cp : copy files and directories

-a   archive    (all files)

-i    interactive

-r    recursive

-u   update

-v    verbose

cp dir1/* dir2



##mv : move/rename file and directories

mv file1 file2      rename

mv file...  directory    move



mkdir : make directories

##rm : remove file and directories

-f    force (no prompt)

e.g.  rm -rf file1 dir1 = rm -r -f file1 dir1



##ln : creat hard and symbolic links

ln file link		hard link

ln -s item link	symbolic link   where "item" is ether a file or a directory



type		indicate how a command name is interpreted

which		display which executable program is executed

man		display a list of command's mannual page

apropos		display a list of appropriate command

info			display a command's info entry

whatis		display a very brief description of a command

alias		creat an alias for a command

help		get help for shell builtins

whatis		display a very brief discription of a command



####info commands

?			display command help

Backspase	display previous page

Spase		display next page

n			next - display the next node

p			previous - display the previous node

u			up - display the parent node of the currency displayed node, usually a manu.

Enter		follow the hyperlink at the cursor location

q			quit

####alias

alias name = 'string'

unalias name		remove an alias

#Redirection

\>	redirecte output to a file

2\>	redirecte error to a file

&\>	both output and error

\> filename	a trick to creat a file

cat filename... \> fikename			concatenate files

cat \> filename	write in a file

cat \< filename	print file content

|

sort			sort lines of text(-u remove repeated lines   -r  sort reversely)

uniq		report or omit repeated lines

wc			print lines, words, and byte counts

grep		print lines matching a pattern (global reguler expression print)

grep -i		ignore case (hu lue dai xao xie)

grep -v		only print lines that didn't match pattern

head filename	print first 10 lines 

tail filename		print last 10 lines

head -n number filename		print first (number) lines 











