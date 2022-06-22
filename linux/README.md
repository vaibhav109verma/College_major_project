# Keylogger

**Keylogger** is simple keylogger for Windows and  Linux
## Installation

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
