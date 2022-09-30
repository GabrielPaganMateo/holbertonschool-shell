# Holberton School Shell Project

### This directory was made to store the tasks and work done as part of the "Shell I/O Redirections & Filters Project"

### Includes scripts with I/O Redirections and Filter commands within the shell

#### Script Descriptions:

0. echo 'Hello, World' {Script that prints hello world followed by a new line to the standard output
1. echo "\"(Ôo)'" {Script that displays a confused smiley
2. cat /etc/passwd {Display the content of the /etc/passwd file
3. cat "/etc/passwd" "/etc/hosts" {Display the contents of /etc/passwd and /etc/hosts
4. tail /etc/passwd {Display the last 10 lines of /etc/passwd
5. head /etc/passwd {Display the first 10 lines of /etc/passwd
6. head -3 iacta | tail +3 {Display the third line of the file iacta
7. echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)" {Create a file named as seen beforehand
8. ls -la > ls_cwd_content {Script that writes into the file ls_cwd_content the result of the command ls -la
9. tail -n 1 iacta >> iacta {Script that duplicates the last line of the file iacta
10. find . -type f -name "\*js" -delete {Script that deletes all the regular files with a .js extension
11. find . -mindepth 1 -type d | wc -l {Script that counts the number of directories and sub-directories 
12. ls -1t | head {Script that displays the 10 newest files in the current directory
13. sort | uniq -u {Script that takes a list of words as input and prints only words that appear exactly once
14. grep root /etc/passwd {Script that displays lines that contain the pattern "root" from the file /etc/passwd
15. grep -c bin /etc/passwd {Display the number of lines that contain the pattern "bin" int the file /etc/passwd
16. grep --after-context=3 root /etc/passwd {Display the lines containing the pattern "root" and 3 lines after them
17. grep -v bin /etc/passwd {Display all the lines in the file /etc/passwd that do not contain the pattern "bin"
18. grep '^[A-Z | a-z]' /etc/ssh/sshd_config {Display all lines of the file /etc/ssh/sshd_config, start with letter
19. tr A Z | tr c e {Replace all characters A and c from input Z and e
20. tr -d c | tr -d {Script that removes all letter c and C from input
21. rev {Script that reverse its input
22. cut -d : -f 1,6 /etc/passwd | sort (Display all users and their home directories, sorted by users n /etc/passwd
23. find . -empty -printf %f'\n' {Command that finds all empty files and directories in current dir and subdir
24. find . -type f -name "\*.gif" | rev | cut -d"/" -f1 | cut -d"." -f2,3 | rev | sort -Vf {list all .gif files
25. cut -c 1 | paste -s -d ' ' | tr -d ' ' {Reorganize an acrostic
26. tail -n +2 | cut -f 1 | sort | uniq -c | sort -n -r | head -n 11 | cut -b 9- {script that parses web servers
