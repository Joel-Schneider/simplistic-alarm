# simplistic-alarm

A really simple alarm clock, that won't stop easily!

# Requires:
The "at" command

# Usage example:
```
$ at 06:30
at> alarm.sh
at> <Ctrl+D>
$
```

To stop the alarm.
```
$ ps aux | grep alarm.sh
...
$ kill <PID of alarm.sh>
$
```
