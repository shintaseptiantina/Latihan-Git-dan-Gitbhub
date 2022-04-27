# Latihan-Git-dan-Gitbhub
USER@ACER MINGW64 ~ (main)
$ pwd
/c/Users/USER

USER@ACER MINGW64 ~ (main)
$ cd folderbaru

USER@ACER MINGW64 ~/folderbaru (main)
$ touch file.txt

USER@ACER MINGW64 ~/folderbaru (main)
$ ls
README.md  file.txt

USER@ACER MINGW64 ~/folderbaru (main)
$ cat file.txt
i need a day between every day
to recover from the day before
and prepare for the day coming

USER@ACER MINGW64 ~/folderbaru (main)
$ git init
Reinitialized existing Git repository in C:/Users/USER/folderbaru/.git/

USER@ACER MINGW64 ~/folderbaru (main)
$ git config --global init.defaultBranch <shinta>
bash: syntax error near unexpected token `newline'

USER@ACER MINGW64 ~/folderbaru (main)
$ git add README.md

USER@ACER MINGW64 ~/folderbaru (main)
$ touch README.md

USER@ACER MINGW64 ~/folderbaru (main)
$ git add .
warning: LF will be replaced by CRLF in file.txt.
The file will have its original line endings in your working directory

USER@ACER MINGW64 ~/folderbaru (main)
$ ls
README.md  file.txt

USER@ACER MINGW64 ~/folderbaru (main)
$ git add README.md

USER@ACER MINGW64 ~/folderbaru (main)
$ git commit -m "first commit"
On branch main
nothing to commit, working tree clean

USER@ACER MINGW64 ~/folderbaru (main)
$ git branch -M main

USER@ACER MINGW64 ~/folderbaru (main)
$ git remote add origin https://github.com/shintaseptiantina/Latihan-Git-dan-Gitbhub.git
error: remote origin already exists.

USER@ACER MINGW64 ~/folderbaru (main)
$ git push -u origin main
