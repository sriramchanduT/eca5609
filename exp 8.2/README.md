# Exp 5.1
## code
```matlab
clc;
clear;
close all;
angle = [-60 -30 0 30 60]; % Steering Angles (degrees)
gain = [9 12 15 12 9]; % Array Gain (dB)
figure
bar(angle, gain)
grid on
xlabel('Steering Angle (Degrees)')
ylabel('Array Gain (dB)')
title('Array Gain for Different Steering Angles')
...
```
## output 
![output](obj8.2.png)
<img width="1337" height="555" alt="obj8 2" src="https://github.com/user-attachments/assets/92a11c0e-4c3f-4142-984e-838426994541" />

