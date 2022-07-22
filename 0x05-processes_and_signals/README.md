# 0x05. Processes and signals

0. What is my PID
Write a Bash script that displays its own PID.

1. List your processes
Write a Bash script that displays a list of currently running processes.

2. Show your Bash PID
Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

3. Show your Bash PID made easy
Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.

4. To infinity and beyond
Write a Bash script that displays To infinity and beyond indefinitely.

5. Don't stop me now!
We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.

6. Stop me if you can
Write a Bash script that stops 4-to_infinity_and_beyond process.

7. Highlander
mandatory
Write a Bash script that displays:
- To infinity and beyond indefinitely
- With a sleep 2 in between each iteration
- I am invincible!!! when receiving a SIGTERM signal


8. Beheaded process
Write a Bash script that kills the process 7-highlander.


9. Process and PID file
Write a Bash script that:
Creates the file /var/run/myscript.pid containing its PID
-Displays To infinity and beyond indefinitely
-Displays I hate the kill command when receiving a SIGTERM signal
-Displays Y U no love me?! when receiving a SIGINT signal
-Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal


10. Manage my process
Programs that are detached from the terminal and running in the background are called daemons or processes, need to be managed. The general minimum set of instructions is: start, restart and stop. The most popular way of doing so on Unix system is to use the init scripts.
Write a manage_my_process Bash script that:
Indefinitely writes I am alive! to the file /tmp/my_process
In between every I am alive! message, the program should pause for 2 seconds


11. Zombie
Write a C program that creates 5 zombie processes.

Requirements:

- For every zombie process created, it displays Zombie process created, PID: ZOMBIE_PID
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- When your code is done creating the parent process and the zombies, use the function bellow
