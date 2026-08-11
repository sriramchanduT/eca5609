# Exp 7.3
## code
```matlab
clc;
clear;
close all;
theta = [-60 -30 0 30 60]; % Main Lobe Direction (degrees)
gain = [1 1 1 1 1]; % Constant normalized gain
figure
polarplot(deg2rad(theta), gain, 'o', 'LineWidth', 2)
title('Main Lobe Direction in Analog Beamforming')
...
```
## output 
![output](obj7.3.png)
<img width="1001" height="530" alt="obj7 3" src="https://github.com/user-attachments/assets/6a119dbd-7e59-460c-a3c1-c727660136ac" />
