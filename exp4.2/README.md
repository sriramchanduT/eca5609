
<img width="1235" height="722" alt="obj2" src="https://github.com/user-attachments/assets/55b73d83-a16d-4ffd-b917-549d43c540a4" />
# Exp 4.2
## code
```matlab
clc; clear; close all;
% Total system resource blocks
total_RB = 50;
% Number of active users
users = 1:5;
% RB allocation to users (example scenario)
alloc = [12 10 9 8 11];
% Resource Block Utilization (%)
util = (alloc / total_RB) * 100;
disp('Resource Block Utilization (%) per User:')
disp(util')
figure
% -------- Graph 1: RB Allocation --------
subplot(2,1,1)
plot(users, alloc, '-o', 'LineWidth', 2)
title('OFDMA Resource Block Allocation per User')
xlabel('User Index')
ylabel('Number of Resource Blocks')
grid on
% -------- Graph 2: Utilization (%) --------
subplot(2,1,2)
plot(users, util, '-s', 'LineWidth', 2)
title('OFDMA Resource Block Utilization (%)')
xlabel('User Index')
ylabel('Utilization (%)')
grid on<img width="1235" height="722" alt="obj2" src="https://github.com/user-attachments/assets/2b6826d3-5970-4368-8bfd-04fe9b6759d0" />

...
```
## output 
![output](obj2.png) 
