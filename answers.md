Q1: What is your home directory?
A: /home/ubuntu

Q2: What is the output of this command?
A:  hello_world.txt

Q3: What is the output of each ls?
A: ls my_folder: 

ls myfolder_2:
hello_world.txt

Q4: What is the output of each?
A: ls my_folder:

ls my_folder2: 

ls my_folder3: 
hello_world.txt

Q5 + Q6: This question deals with getting an error after exiting the AWS shell, and then
attempting to log back in as the newly created sudouser. I actually was not met with any
error, however my method to give sudouser sudo access was a bit different than what most
people did, so instead of explaining the error I will detail how I granted sudouser sudo:
I first logged in as the root:
sudo su -

then I created the new user:
adduser sudouser

then I edited visudo:
sudo -s visudo

add then added sudouser to the list:
sudouser ALL=(ALL) ALL

Q7: What does sudo docker run part of the command do? And what does the salmon swim part do?
A:Salmon is a tool commonly used for RNAseq. sudo docker run executes combinelab/Salmon with docker under sudo abilities.
salmon swim is the command that we executing from combinelab/Salmon. Which in this case prints out the word salmon. 

Q8: What is the output of this command?
A: serveruser is not in the sudoers file.  This incident will be reported.

Q9: What does -c bioconda do? 
A: searches bioconda as an additional channel to search for packages.

Q10: What does the -o athal.ga.gz part of the command do?
A: Saves the file as athal.ga.gz

Q11: What is a gz file?
A: Compressed files on unix like systems

Q12: What does the zcat command do?
A: Basically spits the contents of the file out onto the screen for compressed files

Q13: What does the head command do?
A: Displays the top 10 lines of the file

Q14: What does the number 100 signify in the command? 
A: Displays the top 100 lines of the file instead

Q15: What is | doing? 
A: This is a pipe. Pipes transfer the standard output of one program into the standard input of a second program. 

Q16: What format are the downloaded sequencing reads in? 
A: it downloaded SRR074122.sra

Q17: What is the total size of the disk?
A: 7.7G

Q18: How much space is remaining on the disk?
A: 2.9G

Q19: What went wrong? 
A: There isn't enough disk storage to convert all the reads. 

Q20: What was your solution?
A: add --gzip flag to compress reads
