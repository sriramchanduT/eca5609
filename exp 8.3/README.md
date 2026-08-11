# Exp 8.3
## code
```matlab
clc;
clear;
close all;
desired = [-60 -30 0 30 60]; % Desired Steering Angle (degrees)
actual = [-58 -32 1 29 62]; % Actual Beam Direction (degrees)
error = abs(desired - actual); % Beam Direction Error
figure
plot(desired, error, 'o-', 'LineWidth', 2)
grid on
xlabel('Desired Steering Angle (Degrees)')
ylabel('Beam Direction Error (Degrees)')
title('Beam Direction Error for Different Steering Angles')
...
```
## output 
![output](obj8.3.png)
<img width="1298" height="552" alt="obj8 3" src="https://github.com/user-attachments/assets/b8e92df0-22ab-43e6-ba01-741c28ee3d93" />
