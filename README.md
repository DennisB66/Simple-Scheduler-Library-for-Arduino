# Simple Scheduler Library for Arduino and ESP8266

Simple Scheduler is a small but flexible library for Arduino and ESP8266 that implements a basic time based task scheduler.

Multiple tasks can be attached to a single scheduler that will execute thes taks on a fixed msec interval. Mulple schedulers with each their own msec interval can be defined in parallel.

## Functionality

The functions in the class SimpleScheduler include:
```
constructor     // initialize scheduler with a msec interval
attachHandler() // attach new task handler function
start()         // start scheduler
stop()          // stop scheduler
```

## Library Dependencies

- https://github.com/DennisB66/Simple-Utility-Library-for-Arduino

Version history:
```
0.1			// initial version
0.11        // some cleanup
```
