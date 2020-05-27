# Widya Tracker Configuration

## APN

Kind        |Syntax                                       |Example              |
------------|---------------------------------------------|---------------------|
set         |```setAPN(<apnname>,<username>,<password>)```|```setAPN(internet,,)```|

## Operating Status

***Analog***

Kind        |Syntax                                               |Example              |
------------|-----------------------------------------------------|---------------------|
set         |```setAnalogOperatingStatus(<address>,<min>,<max>)```|```setAnalogOperatingStatus(0,1,1023)```|

> the address has only values 0-2
> min and max have only values 0-4095

***Digital***

Kind        |Syntax                                               |Example              |
------------|-----------------------------------------------------|---------------------|
set         |```setDigitalOperatingStatus(<address>,<mode>,<threshold>)```|```setAnalogOperatingStatus(1,1,400)```|

> addrees value is 0-2.

> mode are two types, namely nc(0) and no(1).

> threshold is parameter to reach true value, the range is 0-1023.

## Interval Publish 

Kind        |Syntax                                               |Example              |
------------|-----------------------------------------------------|---------------------|
set         |```setIntervalPub(<time in second, from 1 until 100>)```|```setIntervalPub(2)```|

## Mode Relay

Kind        |Syntax                                               |Example              |
------------|-----------------------------------------------------|---------------------|
set         |```setModeRelay(<String, "nc" or "no">)```|```setModeRelay(nc)```|
