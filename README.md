# LRC-2-DParityCheck
Longitudinal Redundancy Check (LRC)/2-D Parity Check

Longitudinal Redundancy Check (LRC) is also known as 2-D parity check. In this method, data which the user want to send is organised into tables of rows and columns. A block of bit is divided into table or matrix of rows and columns. In order to detect an error, a redundant bit is added to the whole block and this block is transmitted to receiver. The receiver uses this redundant row to detect error. After checking the data for errors, receiver accepts the data and discards the redundant row of bits.

When a 32-bit block is to be verified, then the following XOR math is performed to determine the LRC bits.

![](https://github.com/eugenedakin/LRC-2-DParityCheck/blob/main/ManualCalculation.png)

Below is a screen grab of the running Xojo program which contains the LRCcalculation method.

![](https://github.com/eugenedakin/LRC-2-DParityCheck/blob/main/LRCScreenGrab.png)
