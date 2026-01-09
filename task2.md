# Module 1: Hello Hackers

### Intro To Commands
Flag: pwn.college{U8pzSLSAGSefgCiDojrtzD6WjfO.QX3YjM1wSM2QjM1EzW}

Solution: I typed 'hello' in the terminal and got the flag.

### Intro To Arguments
Flag: pwn.college{EsVJGn-bSJJ1JRR6JfzkHBL1Kx5.0lNzEzNxwSM2QjM1EzW}

Solution: I typed 'hello hackers' in the terminal and got the flag.

### Command History
Flag: pwn.college{EsVJGn-bSJJ1JRR6JfzkHBL1Kx5.0lNzEzNxwSM2QjM1EzW}

Solution: I used the up arrow in the terminal to view previous commands and found the flag.

# Module 2: Pondering Paths

### The Root
Flag: pwn.college{QAPL72hLjTEZta7yesIbBlk30cF.QX4cTO0wSM2QjM1EzW}

Solution: I ran '/pwn' in the terminal to get the flag.

### Program and Absolute Paths
Flag: pwn.college{gFZ0K7X5peXFz0Dg3pEu_Wn_c2L.QX1QTN0wSM2QjM1EzW}

Solution: I ran '/challenge/run' using the absolute path to get the flag.

### Position Thy Self
Flag: pwn.college{Am8jvtbGylEya1Tbbv6pNTg7acP.QX2QTN0wSM2QjM1EzW}

Solution: I changed directory to /usr/share/doc/fontconfig and ran /challenge/run.

### Position Elsewhere
Flag: pwn.college{sPYzbhxJL63mT3B2G9YbO0s0ait.QX3QTN0wSM2QjM1EzW}

Solution: I changed to different directories and ran /challenge/run five times.

### Implicit Relative Paths, From /
Flag: pwn.college{0XErAMykEQ6LQaMACQ7MvhD8-gw.QX5QTN0wSM2QjM1EzW}

Solution: I changed to / and ran challenge/run using a relative path.

### Explicit Relative Paths, From /
Flag: pwn.college{sCUw3nnaC4nNgbGT1-8x-v0oBwi.QXwUTN0wSM2QjM1EzW}

Solution: I changed to / and ran ./challenge/run using explicit relative path.

### Implicit Relative Paths
Flag: pwn.college{AHmY7sIs8UYXC81XlFB1xlU6Eiz.QXxUTN0wSM2QjM1EzW}

Solution: I changed to /challenge and ran ./run.

### Home Sweet Home
Flag: pwn.college{IVOkigYmw3MHbuRABoNH43MD4Sd.QXzMDO0wSM2QjM1EzW}

Solution: I ran /challenge/run ~/h using the home directory shortcut.

# Module 3: Comprehending Commands

### cat: not the pet, but the command!
Flag: pwn.college{ES-YIPmf2elEKgDHn_ojoboynyt.QXxcTN0wSM2QjM1EzW}

Solution: I used cat /flag to read the file and get the flag.

### catting absolute paths
Flag: pwn.college{wWAGuMvYdR12U31Bf4UsPyMf1uo.QX5ETO0wSM2QjM1EzW}

Solution: I ran cat /flag using an absolute path.

### more catting practice
Flag: pwn.college{gEsmhe4ye-Tglmju0zFC9bTNHVI.QXwITO0wSM2QjM1EzW}

Solution: I used cat /usr/share/groff/flag to read the flag.

### grepping for a needle in a haystack
Flag: pwn.college{4JS_nt-Y59ALMRMw6G690WQZgHC.QX3EDO0wSM2QjM1EzW}

Solution: I ran grep pwn.college /challenge/data.txt to find the flag.

### comparing files
Flag: pwn.college{ccM_AqY_cFpLEPWs3UOsA2dtSZp.01MwMDOxwSM2QjM1EzW}

Solution: I compared the files using diff /challenge/decoys_only.txt /challenge/decoys_and_real.txt to identify the flag.

### listing files
Flag: pwn.college{ooXAyQExkGCk7Rk1WDIXQsdVdHL.QX4IDO0wSM2QjM1EzW}

Solution: I listed files using ls /challenge and ran the renamed challenge file.

### touching files
Flag: pwn.college{YuDJAxLQd_Ts3tn8gx_-4x6JCJ-.QXwMDO0wSM2QjM1EzW}

Solution: I created files using touch and ran /challenge/run.

### removing files
Flag: pwn.college{AA5IvXv8L_Em27VAL5f5vCd3DfI.QX2kDM1wSM2QjM1EzW}

Solution: I removed the file using rm delete_me and verified it with /challenge/check.

### moving files
Flag: pwn.college{sZ8H_xyTq8b1dxDA85BZTsL6Uj5.0VOxEzNxwSM2QjM1EzW}

Solution: I moved the file using mv /flag /tmp/hack-the-planet

### copying files
Flag: pwn.college{QGtbsZvqqsKZb-LaQWwJspMLP_s.0lNxQTMywSM2QjM1EzW}

Solution: I copied the file using cp /flag /tmp/hack-the-planet

### hidden files
Flag: pwn.college{oi6YRHcaQhU8SR2-2bhtFLnXi7G.QXwUDO0wSM2QjM1EzW}

Solution: I used ls / -a to view hidden files and find the flag.

### An Epic Filesystem Quest
Flag: pwn.college{IfNdLu8aQ_Uo1O1V7VujztPxF0Q.QX5IDO0wSM2QjM1EzW}

Solution: I navigated directories using ls, ls -a, cd, and cat to find the flag.

### making directories
Flag: pwn.college{0RueBqI8s7hn3_wjsFR3CzBdNX8.QXxMDO0wSM2QjM1EzW}

Solution: I created a directory with mkdir, added a file, and ran /challenge/run.

### finding files
Flag: pwn.college{wLgun14vkw47YyQurLEMs7nliRi.QXyMDO0wSM2QjM1EzW}

Solution: I used find / -name flag and read it using cat.

### linking files
Flag: pwn.college{YKesl7duJOimUqxDCqxEeWQD4-6.QX5ETN1wSM2QjM1EzW}

Solution: I created a symbolic link using ln -s /flag /home/hacker/not-the-flag and accessed the flag.

# Module 4: Digesting Documentation

### Learning from Documentation
Flag: pwn.college{E7IRkQ-snyBmJzYyeVhC2C_LpVq.QX0ITO0wSM2QjM1EzW}

Solution: I ran /challenge/challenge --giveflag

### Learning Complex Usage
Flag: pwn.college{0oSLNHjEB8gYg4HnwgJOY1J2iwc.QX1ITO0wSM2QjM1EzW}

Solution: I ran /challenge/challenge --printfile /flag

### Reading Manuals
Flag: pwn.college{U-GtSS2ny2361WC477emC-wjWZY.QX0EDO0wSM2QjM1EzW}

Solution: I checked the manual page and ran /challenge/challenge --tnyemw 223

### Searching Manuals
Flag: pwn.college{QdvrGwDv1QVuh_cXxoVptlJjFL5.QX1EDO0wSM2QjM1EzW}

Solution: I searched the manual for flag-related information and ran /challenge/challenge --mtspsh

### Searching for Manuals
Flag: pwn.college{Y_72aFG3dLAogb_Flln6df8EL-_.QX2EDO0wSM2QjM1EzW}

Solution: I searched available manuals using man man, found the correct option man -k challenge, and ran the challenge command.

### Helpful Programs
Flag: pwn.college{QiUiPxBzoQJ3i9jPbu5-nEYg4nL.QX3IDO0wSM2QjM1EzW}

Solution: I used the provided helper option /challenge/challenge -p to get a value and then /challenge/challenge -g 395

### Help for Builtins
Flag: pwn.college{AVRRF62efe_MVjcSGaEaJOjIhRU.QX0ETO0wSM2QjM1EzW}

Solution: I used the help challenge to find the secret value and then challenge --secret AVRRF62e

# File Globbing

### Matching by *
Flag: pwn.college{wLTIfy4xpdiQ-azckOl7FIlf0Ni.QXxIDO0wSM2QjM1EzW}

Solution: I used cd /ch* to go to challenge directory, and ran /challenge/run

### Matching with ?
Flag: pwn.college{0MgtS4DK-V0JTAyNIvzB3fEsRRS.QXyIDO0wSM2QjM1EzW}

Solution: I used cd /?ha??enge to change directories and ran /challenge/run

### Matching with []
Flag: pwn.college{Ux2-4TNW3NXSUIDafluj3qS4Mcx.QXzIDO0wSM2QjM1EzW}

Solution: I used square brackets to match specific characters /challenge/run file_[bash] and passed the file to /challenge/run

### Matching paths with []
Flag: pwn.college{0U0pSZeEnz4Ru-29fcI0WNdCKSy.QX0IDO0wSM2QjM1EzW}

Solution: I used square brackets directly in the path argument /challenge/run /challenge/files/file_[bash]

### Multiple Globs
Flag: pwn.college{kgDQmUVUcATh4WUT7gUbIfneopk.0lM3kjNxwSM2QjM1EzW}

Solution: I used multiple * in a single command /challenge/run *p* to match several files

### Mixing Globs
Flag: pwn.college{AKJF6xdBccX1ns9WQ5sphOGL7RU.QX1IDO0wSM2QjM1EzW}

Solution: I combined character classes /challenge/run [cep]* to match the correct files

### Exclusionary Globbing
Flag: pwn.college{08kksyOGMusdnWvgMhaawSKX3rx.QX2IDO0wSM2QjM1EzW}

Solution: I used exclusionary globbing /challenge/run [^pwn]* to avoid unwanted matches and retrieve the flag.

### Tab Completion
Flag: pwn.college{YddPH5snywKv5BHg6WmM5E4zN5L.0FN0EzNxwSM2QjM1EzW}

Solution: I used the Tab key to auto-complete cat /challenge/pwncollege

### Multiple Options for Tab Completion
Flag: pwn.college{Qtz-sH3hWZ9zMW4pV1hBVbtfCBy.0lN0EzNxwSM2QjM1EzW}

Solution: I pressed Tab twice to view available completion options and selected cat pwncollege-flag

### Tab Completion on Commands
Flag: pwn.college{QRQClvRVCtYEGv-0Z1glsnvOzek.0VN0EzNxwSM2QjM1EzW}

Solution: I used tab completion to complete the challenge command pwncollege-28072

# Module 6: Practicing Piping

### Redirecting Output
Flag: pwn.college{Qy6Cx18bcC0004agVkifntnyy0W.QX0YTN0wSM2QjM1EzW}

Solution: I used > to redirect the output of a command into a file echo PWN > COLLEGE

### Redirecting More Output
Flag: pwn.college{QlQKdbiHQovOohLMqL2eibElQ59.QX1YTN0wSM2QjM1EzW}

Solution: I redirected output from command into the same file using /challenge/run > myflag

### Appending Output
Flag: pwn.college{Qs333g_iCCd62UY8AD9TWZURnvq.QX3ATO0wSM2QjM1EzW}

Solution: I used >> to append command output to an existing file /challenge/run >> /home/hacker/the-flag

### Redirecting Errors
Flag: pwn.college{sga607gEGgd3kJgcNhV-gNNP-yb.QX3YTN0wSM2QjM1EzW}

Solution: I redirected standard error using 2> into a file /challenge/run 1>myflag 2>instructions

### Redirecting Input
Flag: pwn.college{ojqeW2yJhWGFedT5O_0bn8wMbTq.QXwcTN0wSM2QjM1EzW}

Solution: I used < to redirect a file as input to a command /challenge/run < PWN

### Grepping Stored Results
Flag: pwn.college{c77SEwUx_y-HHKccJUYGI5hj79H.QX4EDO0wSM2QjM1EzW}

Solution: /challenge/run > /tmp/data.txt; grep pwn /tmp/data.txt

### Grepping Live Output
Flag: pwn.college{cBvxTKfvbt0KNNHFAqs5gfckDgf.QX5EDO0wSM2QjM1EzW}

Solution: I piped live command output into grep /challenge/run | grep pwn

### Grepping Errors
Flag: pwn.college{wsK4e98fuXeZrhL52ZoeCs3VYMX.QX1ATO0wSM2QjM1EzW}

Solution: I redirected stderr to stdout using 2>&1 and piped it into grep /challenge/run 2>&1 | grep pwn

### Filtering with grep -v
Flag: pwn.college{IttA9Lun7uOL2xmqNWyYbmLOQ-u.0FOxEzNxwSM2QjM1EzW}

Solution: I used grep -v to exclude unwanted lines /challenge/run | grep -v DECOY

### Filtering with sed
Flag: pwn.college{I_D-eMx7q3DMo5KMJrcMqnFGLb4.01NxQTMywSM2QjM1EzW}

Solution: I filtered and modified text output using sed /challenge/run | sed 's/FAKEFLAG//g'

### Duplicating Piped Data with tee
Flag: pwn.college{k8vLN-MK4GrK_eTUoINtK1l_BbW.QXxITO0wSM2QjM1EzW}

Solution: I used tee to send piped output to both a file and the terminal, /challenge/pwn | tee intercepted_output | /challenge/college

### Process Substitution for Input
Flag: pwn.college{UBTJB7VUAyqpd6klazDIUmXhPb6.0lNwMDOxwSM2QjM1EzW}

Solution: I used process substitution <(command) to pass command output as input diff <(/challenge/print_decoys) <(/challenge/print_decoys_and_flag)

### Writing to Multiple Programs
Flag: pwn.college{IFHhNp1jNupXz1gLzXEz2uN6LCx.QXwgDN1wSM2QjM1EzW}

Solution: I used tee with process substitution to write output to multiple programs /challenge/hack | tee >( /challenge/the ) >( /challenge/planet )

### Split-piping stderr and stdout
Flag: pwn.college{gn-gibjQ2fDWoD3RtEnhBk3WNho.QXxQDM2wSM2QjM1EzW}

Solution: I separated standard output and error streams /challenge/hack \ > >( /challenge/planet ) \ 2> >( /challenge/the )

### Named Pipes
Flag: pwn.college{oCaMDYH_viQgEfZz8TW_Wl7E_G2.01MzMDOxwSM2QjM1EzW}

Solution: I created a named pipe using mkfifo, passed data through it. mkfifo /tmp/flag_fifo


# Module 7: Shell Variables 

### Printing Variables
Flag: pwn.college{wopHK5-NSOvapKezQpvDP-U84K4.QX3UTN0wSM2QjM1EzW}

Solution: I used echo $FLAG to print the value of a variable

### Setting Variables
Flag: pwn.college{sc4RlzBIM1yTMWuB2ecRq5N-MTZ.QX5UTN0wSM2QjM1EzW}

Solution: I assigned a value to a variable using PWN=COLLEGE

### Multi-word Variables
Flag: pwn.college{wcNUeV7WOg-C430w3DzpFMGAHFd.QXwYTN0wSM2QjM1EzW}

Solution: I set a variable containing multiple words using quotes PWN="COLLEGE YEAH"

### Exporting Variables
Flag: pwn.college{Ys-Nbpi3Q3ANeAwGLAwc3Z3i08E.QXyYTN0wSM2QjM1EzW}

Solution: I exported a variable using PWN=COLLEGE; COLLEGE=PWN; export PWN; sh; /challenge/run PWN

### Printing Exported Variables
Flag: pwn.college{U_Xo5S4My69nlNwiIO5JtJiXJYp.QX4UTN0wSM2QjM1EzW}

Solution: I printed an exported variable in a child shell using 'env'

### Storing Command Output
Flag: pwn.college{cz7F6VJqUojvhAk93wh-hidsAVz.QX1cDN1wSM2QjM1EzW}

Solution: I stored command output in a variable using PWN=$(/challenge/run); echo $PWN

### Reading Input
Flag: 

Solution: I used the read command to accept user input and retrieved the flag.

### Reading Files
Flag: 

Solution: I read file contents using shell input techniques and obtained the flag.

# Module 8: Data Manipulation

### Translating Characters
Flag: 

Solution: I used the tr command to translate characters in the input and received the flag.

### Deleting Characters
Flag: 

Solution: I used tr -d to delete specific characters from the input and got the flag.

### Deleting Newlines
Flag: 

Solution: I used tr -d '\n' to remove newlines from the output and retrieved the flag.

### Extracting the First Lines with head
Flag: 

Solution: I used the head command to extract the first lines of text and obtained the flag.

### Extracting Specific Sections of Text
Flag: 

Solution: I used text‑processing tools to extract specific sections from the input and got the flag.

### Sorting Data
Flag: 

Solution: I used the sort command to organize data and received the flag

# Module 9: Processes and Jobs

### Listing Processes
Flag:

Solution: I listed running processes using process‑listing commands and identified the required process.

### Killing Processes
Flag:

Solution: I terminated a process using its process ID and completed the challenge.

### Interrupting Processes
Flag:

Solution: I interrupted a running process using a keyboard signal and proceeded to get the result.

### Killing Misbehaving Processes
Flag:

Solution: I forcefully killed an unresponsive process and completed the task.

### Suspending Processes
Flag:

Solution: I suspended a running process and verified its stopped state.

### Resuming Processes
Flag:

Solution: I resumed a suspended process and confirmed it continued execution.

### Backgrounding Processes
Flag:

Solution: I moved a running process to the background and completed the challenge.

### Foregrounding Processes
Flag:

Solution: I brought a background process back to the foreground successfully.

### Starting Backgrounded Processes
Flag:

Solution: I started a process directly in the background and verified it was running.

### Process Exit Codes
Flag:

Solution: I checked the exit status of a process and used it to complete the challenge.

# Module 10: Untangling Users

### Becoming root with su
Flag: 

Solution: I used the `su` command to switch to the root user by providing the correct root password and obtained the flag.

### Other users with su
Flag: 

Solution: I used `su <username>` to switch to another user account and explored their environment to find the flag.

### Cracking passwords
Flag: 

Solution: I cracked the password using the provided password hash and then logged in as the user to retrieve the flag.

### Using sudo
Flag: 

Solution: I checked sudo permissions with `sudo -l`, executed the allowed command with sudo privileges, and found the flag.

# Module 11: Perceiving Permissions

### Changing File Ownership
Flag: 

Solution: I used the `chown` command to change the owner of the file and then accessed it to obtain the flag.

### Groups and Files
Flag: 

Solution: I checked the file’s group ownership using `ls -l`, switched to the correct group, and found the flag.

### Fun With Group Names
Flag: 

Solution: I identified the correct group name, changed the file’s group using `chgrp`, and accessed the file to get the flag.

### Changing Permissions
Flag: 

Solution: I modified the file permissions using `chmod` to allow access and retrieved the flag.

### Executable Files
Flag: 

Solution: I added execute permissions to the file using `chmod +x`, ran the file, and obtained the flag.

### Permission Tweaking Practice
Flag: 

Solution: I adjusted the permissions step by step as required until I was able to read the file and get the flag.

### Permissions Setting Practice
Flag: 

Solution: I set the exact permissions using numeric (octal) values with `chmod` and accessed the file to find the flag.

### The SUID Bit
Flag: 

Solution: I identified the file with the SUID bit set, executed it with elevated privileges, and obtained the flag.

# Module 12: Chaining Commands

### Chaining with Semicolons
Flag: 

Solution: I chained multiple commands using semicolons (`;`) so they executed sequentially and retrieved the flag.

### Building on Success
Flag: 

Solution: I used `&&` to ensure the next command only ran after the previous one succeeded and obtained the flag.

### Handling Failure
Flag: 

Solution: I used `||` so the fallback command executed when the first command failed and found the flag.

### Your First Shell Script
Flag: 

Solution: I created a basic shell script file, added commands to it, ran the script, and obtained the flag.

### Redirecting Script Output
Flag: 

Solution: I redirected the script’s output using `>` or `>>` into a file and read it to get the flag.

### Executable Shell Scripts
Flag: 

Solution: I made the script executable using `chmod +x`, executed it directly, and retrieved the flag.

### Understanding Shebangs
Flag: 

Solution: I added the correct shebang line (`#!/bin/bash`) to the script, ran it successfully, and obtained the flag.

### Scripting with Arguments
Flag: 

Solution: I passed arguments to the script using `$1`, `$2`, etc., and used them to display the flag.

### Scripting with Conditionals
Flag: 

Solution: I used `if`, `else`, and test conditions in the script to meet the requirement and get the flag.

### Scripting with Default Cases
Flag: 

Solution: I used a `case` statement with a default option to handle unexpected input and retrieved the flag.

### Scripting with Multiple Conditions
Flag: 

Solution: I combined multiple conditions using logical operators in the script and obtained the flag.

### Reading Shell Scripts
Flag: 

Solution: I read and analyzed the provided shell script to understand its behavior and locate the flag.

# Module 13: Terminal Multiplexing

### Launching Screen
Flag: 

Solution: I launched a new screen session using the `screen` command and accessed the environment to retrieve the flag.

### Detaching and Attaching
Flag: 

Solution: I detached from the screen session using the detach shortcut and reattached to it later to find the flag.

### Finding Sessions
Flag: 

Solution: I listed active screen sessions using `screen -ls`, reattached to the correct one, and obtained the flag.

### Switching Windows
Flag: 

Solution: I switched between different windows inside the screen session and located the flag.

### Detaching and Attaching (tmux)
Flag: 

Solution: I detached from a tmux session and reattached to it using tmux commands to retrieve the flag.

### Switching Windows (tmux)
Flag: 

Solution: I switched between tmux windows using key bindings and accessed the window containing the flag.

# Module 14: Pondering PATH

### The PATH Variable
Flag: 

Solution: I viewed the current PATH variable using `echo $PATH` and understood how command locations are resolved to obtain the flag.

### Setting PATH
Flag: 

Solution: I modified the PATH variable to include a new directory and then ran the required command to retrieve the flag.

### Finding Commands
Flag: 

Solution: I used `which` and `whereis` to locate the command’s binary and accessed it to get the flag.

### Adding Commands
Flag: 

Solution: I created a new executable file in a directory included in PATH and executed it to obtain the flag.

### Hijacking Commands
Flag: 

Solution: I placed a malicious script earlier in the PATH to hijack the command execution and retrieved the flag.
