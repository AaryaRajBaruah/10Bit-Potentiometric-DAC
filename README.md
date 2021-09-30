# 10Bit Potentiometric DAC
The aim of this project is to design a 10 Bit Potentiometric Digital to Analog Converter with 3.3V analog voltage, 1.8V digital voltage and 1 Off chip external voltage reference by using the sky130 technology.
# Introduction
A Digital to Analog Converter (DAC) converts a digital input signal into an analog signal.The digital signal is represented with binary codes combination of bits 0 and 1




![image](https://user-images.githubusercontent.com/91695207/135533686-c5abc1ed-ee8c-4bd8-aaae-a071743164d3.png)










# Pre Layout Design and Stimulation
The tools used in this stimulation are-

      
# Switch
This switch cirtuit was design using esim. Schematic of the switch circuit is shown below
![switch](https://user-images.githubusercontent.com/91695207/135524504-b4756f01-8489-4ce8-a2c8-2a7b96b5e1fc.png)

Initial transient solution of the switch cirtuit by using pgspice is shown below

![switch ngspice](https://user-images.githubusercontent.com/91695207/135527470-a66a8e56-fdad-45a8-813e-41e30389ffe1.png)

Result Transient analysis is shown below

![switch](https://user-images.githubusercontent.com/91695207/135529497-e9567bdc-bfb4-4b76-a58f-b3451f6965f8.png)

# 2 Bit DAC
This 2 Bit DAC Circuit was design using esim .  Schematic of the 2 Bit DAC is sshown below

![2bit_DAC_A](https://user-images.githubusercontent.com/91695207/135530642-d72cdb4c-1b25-4428-a0bb-97ccf9ca67cb.png)


 Initial transient solution of the 2Bit DAC circuit by using pgspice is shown below
 
 ![2bit](https://user-images.githubusercontent.com/91695207/135531858-a65cd5e3-02c8-4fbf-9440-717465cea8bb.png)


Result transient analysis is shown below

![2bit_DAC output](https://user-images.githubusercontent.com/91695207/135532021-175778be-feda-4b00-91ec-1695fe925886.png)
