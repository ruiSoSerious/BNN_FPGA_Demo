# BNN_FPGA_Demo
The project is created for CIFAR-10 image classification based on BNN (binary neural network) on KC705 FPGA.

The top block diagram is shown as below:

<img width="1148" alt="image" src="https://user-images.githubusercontent.com/60055382/227195497-2255aa79-fd5b-47af-bc3a-71c5c28dbab1.png">

The classification result will send to PC by UART or send to FPGA Board GPIO LEDs as shown below:

<img width="1132" alt="image" src="https://user-images.githubusercontent.com/60055382/227190906-5d092bf7-1342-4d80-b795-231c618f2224.png">

Load BitStrem File onto FPGA Board and 8 GPIO LEDs will showcase the classification result as no 7:

https://user-images.githubusercontent.com/60055382/227480085-63a9c1b0-472f-481f-863c-6f4c87727185.mp4

Open UART Port to receive classification result:

https://user-images.githubusercontent.com/60055382/227481158-f5be56b6-b144-44e7-87e0-0af63f3beb9f.mov

