# tt
A command line time tracking shell script.

## Installation:
Just copy the tt file to your path

## Usage:

```tt start [taskname]```

Start tracking time for a task.

```tt start taskname [time]```

Start tracking time for a task from some time ago.    
example:    
    tt start Task23 1hour    
    tt start Task42 1min    
    tt start Task43 54sec    

```tt status```
	
  Display the time tracked so far for the current task.

```tt stop```

  Display the raw masterlist (for piping into other programs)

```tt raw```

Stop tracking the current task.

```tt display [day|week|month|year|all]```

Display tracked time (default is month).

```tt delete [all]```

Delete the previous task or all tasks.

```tt help```

Display this help text.

Configuration:
The default configuration files are located in ~/.config/tt/
This directory can be changed using the \$TITTY_CONFIG_DIR environment variable.
