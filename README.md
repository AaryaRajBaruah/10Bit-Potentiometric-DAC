# 10Bit Potentiometric DAC
The aim of this project is to design a 10 Bit Potentiometric Digital to Analog Converter with 3.3V analog voltage, 1.8V digital voltage and 1 Off chip external voltage reference by using the sky130 technology.
# Introduction
A Digital to Analog Converter (DAC) converts a digital input signal into an analog signal.The digital signal is represented with binary codes combination of bits 0 and 1




![image](https://user-images.githubusercontent.com/91695207/135533686-c5abc1ed-ee8c-4bd8-aaae-a071743164d3.png)










# Pre Layout Design and Stimulation
The tools used in this stimulation are:
- esim
- pgspice
- sky130
      
# Switch
This switch cirtuit was design using esim. Schematic of the switch circuit is shown below

![Annotation 2021-10-01 051020](https://user-images.githubusercontent.com/91695207/135614528-86804e4e-246a-4323-aa27-5d8ddaf5a52b.png)
![switch](https://user-images.githubusercontent.com/91695207/135524504-b4756f01-8489-4ce8-a2c8-2a7b96b5e1fc.png)

Initial transient solution of the switch cirtuit by using pgspice is shown below

![switch ngspice](https://user-images.githubusercontent.com/91695207/135527470-a66a8e56-fdad-45a8-813e-41e30389ffe1.png)

Result Transient analysis is shown below

![switch](https://user-images.githubusercontent.com/91695207/135615926-bbc95419-a63b-407c-8b47-30ea61c58650.png)


# 2-Bit DAC
This 2 Bit DAC Circuit was design using esim .  Schematic of the 2-Bit DAC is sshown below

![2bit](https://user-images.githubusercontent.com/91695207/135616348-90096ddc-b37e-4f99-813e-12200c9383c8.png)
![2bit_DAC_A](https://user-images.githubusercontent.com/91695207/135530642-d72cdb4c-1b25-4428-a0bb-97ccf9ca67cb.png)


 Initial transient solution of the 2Bit DAC circuit by using pgspice is shown below
 
 ![2bit](https://user-images.githubusercontent.com/91695207/135531858-a65cd5e3-02c8-4fbf-9440-717465cea8bb.png)


Result transient analysis is shown below

![2bit output](https://user-images.githubusercontent.com/91695207/135616389-8782ba56-1b99-41f1-8155-1b447f0d04be.png)

# 3-Bit DAC
This 3-Bit DAC Circuit was design using esim. Schematic of the 3-Bit DAC is shown below


![3bit](https://user-images.githubusercontent.com/91695207/135644505-e2f6f8cb-257f-4e05-8dee-fe2832e0abdb.png)
![3 bit scham](https://user-images.githubusercontent.com/91695207/135644446-30dc559d-1747-42df-8d4c-d33f64d44dd2.png)

Initial transient solution of 3-Bit DAC circuit by using pgspice is shown below

![3bit initial](https://user-images.githubusercontent.com/91695207/135644833-b14c0a7c-06b0-4bc9-b50c-aabd3dc6103e.png)


Result transient analysis is shown below

![3bit output](https://user-images.githubusercontent.com/91695207/135646067-aa4461c0-0040-44d9-95ad-af4ffc31f763.png)

# 4-Bit DAC
This 4-Bit DAC circuit is design using esim . Schematic of the 4-Bit DAC is shown below


![4 bit](https://user-images.githubusercontent.com/91695207/135667714-7181f219-1a46-4440-8d93-806abb91f23a.png)
![4 bit sch](https://user-images.githubusercontent.com/91695207/135667691-8e5c43f6-4f10-49bb-8ecb-d759498c35f2.png)




Initial transcient solution is shown below


![4 bit initial](https://user-images.githubusercontent.com/91695207/135667655-00961884-832b-45ba-bf4d-4efc2d5336d7.png)





Result transient analysis is shown below

![4bit ouitput](https://user-images.githubusercontent.com/91695207/135667631-3e3e57be-fb87-47af-b94b-9abace972584.png)

