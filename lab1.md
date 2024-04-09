**Commands with no arguments**
* `cd` : Running this command with no arguments just took me to my home directory, this occurred because I didn't give it any instructions on where to take me. The output was not an error, because it is a valid command that interprets it as a request to take me to my home directory, which was `/Users/arianalopezleon`
* `ls` : Running this command with no arguments made it list the contents of the home directory, `/Users/arianalopezleon`, this occurred because I didn't provide any specific file or directory from which to list the content from. The output was not an error because it uses the current home directory as an argument if there isn't any written.
* `cat` : Running this command with no arguments didn't produce any outputs, instead, it kept on waiting for input from the user, this occurs due to the way `cat` is designed to function. The output of this command was not an error because it kept on waiting for a user input, and waiting for input is a valid behavior for `cat`.


**Commands with directory as an argument**
  * `cd`: Running this command with `cse15l-lab-reports` as the argument, changed my home directory, `/Users/arianalopezleon`, to the one I wrote, so the output was `/Users/arianalopezleon/cse15l-lab-reports`. This occurred because `cd` is designed to change the curent directory to the one I specified in the argument. The output was not an error because the command `cd`, received a directory as an argument and it was a valid path.
  * `ls` : Running this program listed the files in the directory that I wrote as the argument, and I got this output because `ls` receives the specified directory from which you want to see it's contents, and then it list everything that is inside that directory. The output was not an error because it was a valid argument from which the command `ls` was able to receive specific instructions to print the contents from a directory that was part of a valid path.
  * `cat` : I got the output of an error when I ran this command with the argument,`cse15l-lab-reports` because it was a directory and this command expects files as arguments. Since `cat` is used to display contents of files, when i placed the directory as an argument, it wasn't able to detect any files, and it could not print anything, instead it showed an error, `../cse15l-lab-reports: Is a directory`.


 **Commands with a file as an argument**
   * `cd` : Running this command with the file `./es_txt.md` as an argument, produced an error because I placed a file, instead of a directory. The error showed how `cd` is meant to change directories and when a file is placed instead of a directory, it does not align with the functionality of the command.
   * `ls`: I got the output `es_txt.md` because I told the command to list everything about the file `es_txt.md`, and it was just able to display what it knows about the file, which is its title. This is not an error because `ls` doesn't only provide directory content, but it also gives information about files, and I instructed it to list all the information about `es_txt.md`.
   * `cat` : I got the output `Hola Mundo!!` because I told the command to display everything inside the file `es_txt.md`, and that was what was inside the file. This was not an error because `cat` received the name of a file, and it was able to align it with its intended functionality.


