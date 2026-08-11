# Exp 6.3
## code
```matlab
clc;
clear;
close all;
scs = [15 30 60 120 240]; % Subcarrier Spacing (kHz)
symbols = [14 14 14 14 14]; % OFDM Symbols per Slot
figure
bar(scs, symbols)
grid on
xlabel('Subcarrier Spacing (kHz)')
ylabel('Number of OFDM Symbols')
title('OFDM Symbols per Slot for Different Subcarrier Spacing')
ylim([0 16])
...
```
## output 
![output](obj6.3.png)
<img width="1248" height="582" alt="obj6 3" src="https://github.com/user-attachments/assets/5bbf7673-36bf-4fec-8aec-74a4d596922a" />
