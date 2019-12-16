# Java Logic Using RGB Color Values

After understanding how to distinguish the color values of Red and Blue, you can use that to create logic statements that allow your robot to do the same.

With the REV Color/Range Sensor V3 attached facing downward and the LED on, you should be able to determine whether or not your robot is seeing the Red or Blue tape or just the gray using the following logic.

If (RedValue > 127.5 and BlueValue < 127.5)
 
 The Robot sees Red tape

Else If (RedValue < 127.5 and BlueValue > 127.5)

 The Robot sees Blue tape
 
Else

 The Robot sees the Gray mat.
 
You can use this Logic in a while loop as shown in the programs that are also included in the Repository.
