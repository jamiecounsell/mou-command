##Mou /bin/bash
A quick bash script to open files from the command line without setting Mou as your default program for `.md` files.

###Installation
Simply copy `mou` to your target bin directory (`/bin/`, `/usr/bin/`, `/usr/local/bin/`, etc.) and give it the proper permissions.  

```
$ cp mou /usr/bin/mou
$ chmod +x /usr/bin/mou
```
###Usage
To open a file, simply use the `mou` command.  

```
$ mou my_file.md
```

mou-command also supports opening multiple files

```
$ mou my_file.1.md my_file.2.md
```

If the file does not exist, it will be created with the .md extension. (If you enter the extension, it will not create two)

```
$ mou my_new_file my_other_file.md
$ ls 
  my_new_file.md  my_other_file.md

```