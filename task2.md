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
