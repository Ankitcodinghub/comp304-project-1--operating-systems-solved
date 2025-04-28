# comp304-project-1--operating-systems-solved
**TO GET THIS SOLUTION VISIT:** [COMP304 Project 1- Operating Systems Solved](https://www.ankitcodinghub.com/product/comp-304-operating-systems-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117706&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP304  Project 1- Operating Systems Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
GitHub Classroom Link: https://classroom.github.com/a/s8hwXLGK

Description

The main part of the project requires you to develop an interactive Unix-style operating system shell, called Mishell in C. After executing Mishell, it will read commands from the user and execute them. Some of these commands will be builtin commands, i.e., specific to Mishell and not available in other shells, while others will be regular programs such as ls and echo. The project has four main parts (95 points) in addition to a report (5 points). We suggest starting with the first part and building the rest on top of it.

Part I (15 points)

• Use the skeleton program provided as a starting point for your implementation. The skeleton program reads a line of commands from stdin, parses it, and separates it into arguments using whitespace as the delimiter. You will implement the action that needs to be taken based on the command and its arguments entered in Mishell. Feel free to modify the command line prompt and parser as you wish.

• Use the provided Makefile to compile your code. Type make help to get a list of build targets.

1

• Command line inputs, except those matching builtin commands, should be interpreted as program invocation. The shell must fork and execute the requested programs. Refer to Part I – Creating a child process of the book.

• The shell must support background execution of programs. An ampersand (&amp;) at the end of the command line indicates that the shell should return the command line prompt immediately after launching the program.

• Do not use the exec() family of calls that are prefixed with p such as execp() that automatically search for executable files. Instead, use the execv() library call and implement path resolution yourself.

• Implement cd and exit builtin commands.

Part II (10 points)

• In this part of the project, you will implement I/O redirection for Mishell. Implement the following operators:

– Operator &gt; : The file is created if it does not exist, and truncated otherwise.

– Operator &gt;&gt;: Same as above, but the output is appended if the file already exists. – Operator &lt; : The input of the program on the left-hand side is read from a file.

A sample command line is given for I/O redirection below.

$ program arg1 arg2 &gt; output.txt &gt;&gt; append.txt &lt; input.txt

You can use dup() and dup2() system calls for this part. Refer to the bash manual on redirections for more info.

Part III (10 + 15 + 15 + 10 points)

In this part of the project, you will implement new Mishell commands (builtin commands).

1. Dice Roll (10 points)

Write a program to roll multi-sided dices and display the results individually with the sum at the end. Syntax:

$ roll [number of rolls]d&lt;number of sides&gt;

Example output:

$ roll 3d6

Rolled 17 (3 + 5 + 4)

$ roll 4d10

Rolled 27 (3 + 10 + 9 + 5)

$ roll d3

Rolled 2

• Notice that the number of rolls is optional. If not provided, assume a single roll.

• Make sure to handle malformed input and other possible errors.

2. cd history (15 points)

Implement a command called cdh. The command takes no arguments. When called, the command should output a list of 10 most recently visited directories. The list should also include an index for each directory as both a number and an alphabetic character. The command should then prompt the user the directory they want to navigate to. The user can select either a letter or a number from the list. After this, the shell should change into the selected directory. Make sure not to include the same directory twice. Below is example output for 5 most recent directories.

Keep in mind that this command lives across shell sessions; when a new shell session is started, it should remember recently visited directories of previous sessions.

Note: the command is inspired by the cdh command from the fish shell. You can take a look at its documentation for more details.

3. Count Lines of Code (15 points)

Implement a command called cloc to recursively count lines of code for all source code files in a given directory.

The output below is from the cloc utility that has support for many languages. Your version does not need to be similarly comprehensive, however, and you are only expected to implement it for C, C++, Python, and can assume every other file type to be Text (.txt). You also do not need to calculate performance metrics such as lines per second as shown in the screenshot.

• Print the total number of files found

• Print the number of files that are processed, ignoring binary files and dotfiles (files and directories that start with a .)

• List each file type or language with the number of files, total number of blank lines, comment lines, and code lines. You can alternatively list by file extension as opposed to language names shown in the screenshot, for example, .c, .py, .txt, and so on. • Print a collective sum of all blank, commend and code lines in all files as shown in the screenshots.

4. Custom Command (10 points) [Can be written in any language]

The final command is any new Mishell command of your choice. Come up with a new command that is not too trivial and implement it inside your shell as a builtin. Be creative. Selected commands will be shared with your peers in the class. You are allowed to take inspiration from existing Linux programs or existing shell builtins, but do not make an exact clone.

Note: If you are implementing this project as a team, both partners are required to implement their own custom commands, and the report must include explanations of both commands.

Part V (20 points)

Psvis &lt;PID&gt;&lt;output file&gt; (Must be written in C):

You are required to implement the psvis command which uses a kernel module. The command finds the subprocess tree by treating the give PID as the root and visualizes it in a human-friendly graph form. A node in the graph represents a process and an edge represents the parent-child relationship between two processes. In each node, show the PID and creation time of the process. The heir nodes (the eldest child of a parent) should be colored with a district color. For visualization, the graph should be dumped into an image file.

• To develop this command, an underlying kernel module is required to handle the process tree. The visualization part does not need to be handled inside the kernel module. You need to be a superuser in order to complete this part of your assignment. The command psvis should trigger the kernel module.

• You will need to explore the Linux task struct defined in linux/sched.h to obtain necessary information such as process name and process start time.

• Test your kernel module first outside of Mishell and make sure it works.

• When the command is called for the first time, Mishell will prompt sudo password to load the module into the kernel. Successive calls the command will notify the user that the module is already loaded.

• Mishell should remove the module from kernel when the shell is exited

• You can use pstree command to check if the process list is correct. Use the -p flag to list the processes with their PIDs.

Note: You need to be in a working directory with no spaces in the path to build the kernel module with the provided Makefile.

References

• Though we are not doing the same exercise as the book, Project 2 = linux Kernel Module for Listing Tasks discussion from the book might be helpful in implementing Part V.

• Writing a simple kernel module: https://devarea.com/linux-kernel-development-and-writing-a-simple-kernel-module/

• Task Linked List (scroll down to Process Family Tree):

https://www.informit.com/articles/article.aspx?p=368650

• Linux Cross-Reference: https://elixir.bootlin.com/linux/latest/source

• Passing Arguments to a Kernel Module:

https://www.tldp.org/LDP/lkmpg/2.4/html/x354.htm

Deliverables and Requirements

You are required to submit the following in a zip file (name it username1-username2.zip) to Blackboard. • You must push your work to GitHub classroom in addition to Blackboard submissions. We will be checking the commits throughout the and during project evaluation.

• Although not required, we highly encourage you to use the provided .clang-format file to autoformat your code. Run the following command to apply formatting.

find . -name ’*.[ch]’ -exec clang-format -i {} ;

• .c source file that implements the Mishell shell. Please add comments to your implementation.

• .c source file of the Kernel module used by psvis.

• Any supplementary files for your implementation (Makefiles, header files, etc.)

• Implement and test your code in a Linux environment.
