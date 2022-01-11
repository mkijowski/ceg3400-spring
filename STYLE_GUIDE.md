## Guide to markdown style

[Follow this markdown cheat-sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

* When in doubt ask or use your best judgment
* Keep answers in-line as much as possible.
* Use back-tics (\`example\`) to highlight commands, arguments, and files/paths.
* Use triple back-tics to highlight whole sections of code, multiple lines of output, or portions of a file.
* [Write good commit messages](https://chris.beams.io/posts/git-commit/)
* Make it look good!
* pro tip, make it look good both in text format and markdown format

---

## Keeping answers inline

When answering questions, keep them in-line but below the question.  Below are ***good*** responses.

* For instance, what is your favorite color

  Blue

* Next question
  * next answer

```
* For instance, what is your favorite color

  Blue

* Next question
  * next answer
```

Notice the extra newline between the first question and answer, this is required to have it shown in a new paragraph. 
The indentation before the answer allows it to be a part of the same bullet point 

---

## Bad examples

```
* What is your favorite food
  pizza
```

* What is your favorite food
  pizza

---

Worse yet:
```
* What is your favorite color?
* What is the hex value of that color?
* How many of that color items are in your backpack?
Blue
000ff
13
```

* What is your favorite color?
* What is the hex value of that color?
* How many of that color items are in your backpack?
Blue
000ff
13

---

Files (especially paths) and commands can be surrounded by single back-tics  \`example\` -> `example`

Triple back-tics allow for multi line code highlighting, useful for pasting the output of commands:
```
mkijowski@pop-os:~/3400$ ls -lah
total 232K
drwxrwxr-x  4 mkijowski mkijowski 4.0K Sep 20 22:05 .
drwxr-xr-x 26 mkijowski mkijowski 4.0K Sep 20 23:27 ..
-rw-rw-r--  1 mkijowski students  198K Sep 20 09:12 allkeys
-rwxrwxr-x  1 mkijowski mkijowski  112 Sep 19 10:19 coingrader.sh
drwxrwxr-x  2 mkijowski mkijowski 4.0K Sep 20 17:18 dictionaries
-rw-rw----  1 mkijowski grader    1.4K Sep 14 20:05 key-sign-grades
drwxrwxr-x  2 mkijowski mkijowski 4.0K Sep 20 18:02 lab1
-rwxrwxr-x  1 mkijowski mkijowski  413 Sep 14 14:15 miner.sh
-rw-------  1 mkijowski mkijowski   16 Sep 20 22:05 private-key
```

Note: triple back-tics will not line wrap, so you should probably format that a little bit yourself...
