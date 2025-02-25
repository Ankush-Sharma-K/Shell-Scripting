# Shell Scripting
* A code file with .sh extension, in which a script is written it will do a specific task on executing.
* Its main use is to automate the repetitive tasks like back up, cleaning chunk, etc.
* System monitoring

**Disadvantages**
* Slow Execution speed.
* Not well suited for complex tasks.
* A single mistake will change the whole script and can be proven harmful.

# Some Important commands of Bash:

**To Know the username:**
```bash
whoami
```
**To check another shells present on system**
```bash
cat /etc/shells
```
**cat**
* It is a powerful and useful command to manipulate files.
* We can **read a file using cat command**
```bash
cat filename.txt
```
**Combine multiple files in a single new file**
```bash
cat file1.txt file2.txt > newfile.txt
