# ti-tty
A command line time tracking shell script.

## Installation:
Just copy the titty file to your path

## Usage:

```titty start [taskname]```

Start tracking time for a task.

```titty start taskname [time]```

Start tracking time for a task from some time ago.    
example:    
    titty start Task23 1hour    
    titty start Task42 1min    
    titty start Task43 54sec    

```titty status```
	
  Display the time tracked so far for the current task.

```titty stop```

Stop tracking the current task.

```titty display [day|week|month|year|all]```

Display tracked time (default is month).

```titty delete [all]```

Delete the previous task or all tasks.

```titty help```

Display this help text.

Configuration:
The default configuration files are located in ~/.config/titty/
This directory can be changed using the \$TITTY_CONFIG_DIR environment variable.
