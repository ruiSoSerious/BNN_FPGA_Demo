# BNN_FPGA_Demo
The project is created for CIFAR-10 image classification based on BNN (binary neural network) on KC705 FPGA.

The top block diagram is shown as below:

<img width="1148" alt="image" src="https://user-images.githubusercontent.com/60055382/227195497-2255aa79-fd5b-47af-bc3a-71c5c28dbab1.png">

The classification result will send to PC by UART or send to FPGA Board GPIO LEDs as shown below:

<img width="1132" alt="image" src="https://user-images.githubusercontent.com/60055382/227190906-5d092bf7-1342-4d80-b795-231c618f2224.png">

Load BitStrem File onto FPGA Board:

https://user-images.githubusercontent.com/60055382/227243672-6ede7c62-3842-4a20-8ef2-168627909312.MOV

Open UART Port to receive classification result:

https://user-images.githubusercontent.com/60055382/227241696-c738a180-a043-42d0-ad08-e7e0a558d34f.MOV

