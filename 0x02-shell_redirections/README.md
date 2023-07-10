> # Shell I/O Redirections Scripts

This folder contains scripts written using emacs for Ubuntu 20.04 LTS at exactly 2 lines long to perform the folowing tasks:
<ol>
<li> <code>0-hello_world </code>: Prints “Hello, World”, followed by a new line to the standard output.</li>
<li> <code>1-confused_smiley </code>: displays a confused smiley '(Ôo)'.</li>
<li> <code>2-hellofile </code>: Display the content of the /etc/passwd file.</li>
<li> <code>3-twofiles </code>: Display the content of /etc/passwd and /etc/hosts</li>
<li> <code>4-lastlines </code>: Display the last 10 lines of /etc/passwd</li>
<li> <code>5-firstlines </code>: Display the first 10 lines of /etc/passwd</li>
<li> <code>6-third_line </code>: Displays the third line of the file iacta without the use of <code>sed</code></li>
<li> <code>7-file </code>: Creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.</li>
<li> <code>8-cwd_state </code>: Writes into the file ls_cwd_content the result of the command ls -la</li>
<li> <code>9-duplicate_last_line </code>: Write a script that duplicates the last line of the file iacta</li>
<li> <code>10-no_more_js </code>: Deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.</li>
<li> <code>11-directories </code>: Counts the number of directories and sub-directories in the current directory. 
<ul>
<li>The current and parent directories should not be taken into account</li> 
<li>Hidden directories should be counted</li>
</ul></li>
<li> <code>12-newest_files </code>:  Displays the 10 newest files in the current directory with one file per line sorted from the newest to the oldest.</li>
<li> <code>13-unique </code>: Takes a list of words as input and prints only words that appear exactly once.
<ul>
<li>Input format: One line, one word</li> 
<li>Output format: One line, one word</li>
<li>Words should be sorted</li>
</ul></li>
<li> <code>14-findthatword </code>: Display lines containing the pattern “root” from the file <code>/etc/passwd</code></li>
<li> <code>15-countthatword </code>: Display the number of lines that contain the pattern “bin” in the file <code>/etc/passwd</code></li>
<li> <code>16-whatsnext </code>: Display lines containing the pattern “root” and 3 lines after them in the file <code>/etc/passwd</code>.</li>
<li> <code>17-hidethisword </code>: Display all the lines in the file <code>/etc/passwd</code> that do not contain the pattern “bin”.</li>
<li> <code>18-letteronly </code>: Displays all lines of the file /etc/ssh/sshd_config starting with a letter including capital letters as well.</li>
<li> <code>19-AZ </code>: Replaces all characters A and c from input to Z and e respectively.</li>
<li> <code>20-hiago </code>: Removes all letters c and C from input.</li>
<li> <code>21-reverse </code>: Reverses its input.</li>
<li> <code>22-users_and_homes </code>: displays all users and their home directories, sorted by users based on the the <code>/etc/passwd</code></li>