
Assignment 0
1. Read notes on timer and polling loop
2. Debug bwio - later
3. A0

1. Digital clock showing minutes, seconds and tenths of seconds, measures time intervals accurately, in the sense that it does not slow down or lose ticks. 
2. cli to the track that sets train speeds and switches turn-outs
3. real-time display on the terminal showing the state of the track. 


Digital clock: 

Use Timer3 (32 bits)

load: 0xffffffff
control: 
- enable
- mode not set
- clksel set

Test: run a program to read value from timer every 10 ticks. 

Train Commands: 

1. tr <train_number> <train_speed> – Set any train in motion at the
desired speed (0 for stop).
2. rv <train_number> – The train should reverse direction. To reverse
direction set the train speed to zero, wait until the train stops, send
the reverse direction command, then send a speed command to reaccelerate
the train. The assumption is that the train will go the same
speed in reverse as it was going forward before the command.*
3. sw <switch_number> <switch_direction> – Throw the given
switch to straight (S) or curved (C). Do not under any circumstances
activate a switch over and over again. Doing so will burn out the
solenoid, thereby pissing off all of the following: me, the TAs, your
classmates and Fraser.
4. q – halt the system and r eturn to RedBoot.

tr (train_number, train_speed)

rv (train_number)

sw(switch_number, switch_direction)

q ()

COM1: train set
COM2: terminal


io

ioputc
iogetc
cursor addressing