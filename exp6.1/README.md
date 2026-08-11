# Exp 6.1
## code
```matlab
clc;
clear;
close all;

scs = [15 30 60 120 240]; % Subcarrier Spacing (kHz)
mu = 0:4; % Numerology Index
bar(scs)
grid on
set(gca,'XTick',1:5)
set(gca,'XTickLabel',mu)
xlabel('Numerology Index (\mu)')
ylabel('Subcarrier Spacing (kHz)')
title('5G NR Subcarrier Spacing for Different Numerologies')
...
```
## output 
![output](obj6.1.png)
<img width="1237" height="586" alt="obj6 1" src="https://github.com/user-attachments/assets/e63f0a3d-e0ff-485f-918f-851b3147a6fc" />
