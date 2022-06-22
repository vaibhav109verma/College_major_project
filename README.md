# A simple keylogger for Windows, Linux and Mac

A keylogger is a program that records your keystrokes, and this program saves them in a log file on your local computer.
Currently, there are two keylogger programs for the major operating systems; Windows and Linux.

###Installation
## Windows
To change visibility of the window set the `#define` in line 9 to `visible` or `invisible`.

Simply compile into an .exe, and then run. Visual Studio is good for this.

- `invisible` makes the window of the logger disappear, and it also starts up hidden from view. Note that it is still visible in the task manager.
- `visible` is visible, and the window does not close when typing. Great for testing it out.

Both of these save the keystrokes to a .txt file when closed.

> Note that sometimes your compiler may through up errors. If it does, keep compiling - the program still works. As always, please create an issue if you have a problem.

## Linux

### Installation


The following instructions will install Keylogger using pip3 .

```
  pip3 install -r requirements.txt
```
or 
```
  pip3 install pyxhook
```

## How to run it

By running `nohup python3 keylogger.py &` command, it'll start to log your strokes:
The meaning of nohup is ‘no hangup‘.
When nohup command use with ‘&’ then it doesn’t return to shell command prompt after running the command in the background. 
```
$~/Keylogger/linux$ nohup python3 keylogger.py &

$:~/Keylogger/linux$ fg

```

The Keylogger is now running! It will log your strokes to a file .
Stop it by typing the command `fg` then hitting `CTRL+C`

---

---
#### Uses

Some uses of a keylogger are:

- Business Administration: Monitor what employees are doing.
- School/Institutions: Track keystrokes and log banned words in a file.
- Personal Control and File Backup: Make sure no one is using your computer when you are away.
- Parental Control: Track what your children are doing.
- Self analysis

---

