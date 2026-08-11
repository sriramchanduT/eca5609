# Exp 7.1
## code
```matlab
clc;
clear;
close all;
antennas = [2 4 8 16 32]; % Number of Antenna Elements
gain = 10*log10(antennas); % Beamforming Gain (dB)
figure
bar(antennas, gain)
grid on

xlabel('Number of Antenna Elements')
ylabel('Beamforming Gain (dB)')
title('Beamforming Gain for Different Antenna Array Sizes')
...
```
## output 
![output](obj7.1.png)
<img width="1251" height="551" alt="obj7 1" src="https://github.com/user-attachments/assets/1ef31e04-7ec3-41df-97fc-bc3d5563934e" />
