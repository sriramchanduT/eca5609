# Exp 8.1
## code
```matlab
clc;
clear;
close all;
angle = [-60 -30 0 30 60]; % Steering Angles (degrees)
gain = ones(size(angle)); % Normalized Gain
figure
polarplot(deg2rad(angle), gain,'o-','LineWidth',2)
title('Steering Angle Variation in MIMO Beamforming')
...
```
## output 
![output](obj8.1.png)
<img width="855" height="587" alt="obj8 1" src="https://github.com/user-attachments/assets/308508af-bf13-4bae-b3ea-7f959af28cd1" />
