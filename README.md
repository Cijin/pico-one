# Diplay driver notes [WIP]

### Write mode: I2C-bus data format
![2025-03-12_09-19](https://github.com/user-attachments/assets/a035a66b-44df-413e-a49a-506b1df0d84e)


1. Slave address:
   a. `0 1 1 1 1 0 SA0 R/W#`
   b. `0 1 1 1 1 0 0 1` for read
   c. `0 1 1 1 1 0 0 0` for write
2. Control/Data byte(s):
   a. `C0 D/C# 0 0 0 0 0 0`
   b. 
