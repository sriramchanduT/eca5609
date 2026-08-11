# Exp 7.2
## code
```matlab
clc;
clear;
close all;
antennas = [2 4 8 16 32]; % Number of Antenna Elements
beamwidth = [90 45 22.5 11.25 5.625]; % Beam Width (degrees)
figure
plot(antennas, beamwidth,'o-','LineWidth',2)
grid on

xlabel('Number of Antenna Elements')
ylabel('Beam Width (Degrees)')
title('Beam Width for Different Antenna Array Sizes')
...
```
## output 
![output](obj7.2.png)
<img width="1251" height="548" alt="obj7 2" src="https://github.com/user-attachments/assets/89fab174-4735-4e2c-b838-f712ca133fb2" />
