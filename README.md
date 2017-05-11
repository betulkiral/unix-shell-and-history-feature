# unix-shell-and-history-feature
This program code serves as a shell interface. 
Shell interface accepts user commands and then runs a separate process.
In response to the user, the command prompt is entered as follows, then the system waits for the user to enter the command and the entered command is executed.
<br/><br/>
 Step 1:  <b>osh></b><br/>
 Step 2:  <b>osh>ls</b><br/>

The waiting relationship between parent and child can be two format. <br/>

<b> 1. </b> The parent process waits for the child process to finish. <br/>
<b> 2. </b> Parent and child work concurrently. This situation is valid when the "&" character is wrote at the end of the command.
Sample Usage : <b> osh>ls & </b> <br/>

If the user enters exit command in command line, this application terminate. Sample Usage : **osh>exit** <br/>

Another special feature of the project is that it supports a special history command.
For example, when the <b>"osh> history"</b> command is typed, the 10 commonly used commands are listed together with the usage numbers.<br/>

 




