# STM32-UART-VSCODE-WOKWI-SERIALPLOTTER-SIMULATION
A project demonstrating UART communication between STM32 and PC, simulated via Wokwi with Serial Plotter display.

Step 1: Peripheral Configuration with STM32CubeMX
Initialize the project, configure the system clock, and enable UART1 peripherals using STM32CubeMX. Generate the code using the Makefile toolchain.
![alt text](image-1.png)
![alt text](image.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-16.png)

Step 2: Firmware Migration to PlatformIO
Migrate the generated source files by copying the contents of the Inc/ and Src/ folders from the CubeMX project into the include/ and src/ directories of your PlatformIO project.
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)

Step 3: Wokwi Simulator License Activation
Set up the Wokwi extension in VS Code and obtain a Wokwi API Key/Token for local simulation support.
![alt text](image-8.png)
![alt text](image-9.png)
![alt text](image-10.png)
![alt text](image-11.png)
![alt text](image-12.png)

Step 4: Hardware Diagram Synchronization
Synchronize the hardware configuration by copying the JSON definitions from the Wokwi web interface into the local diagram.json file in VS Code.
![alt text](image-13.png)
![alt text](image-14.png)
![alt text](image-15.png)
Step 5: STM32L031K6 Hardware Modeling
Design and instantiate the STM32L031K6 (Nucleo-32) board model within the VS Code environment to match the physical pinout and connections.
Step 6: Core Implementation & UART Logic
Implement the essential code blocks for UART data transmission/reception and verify the logic using the integrated Serial Plotter.
![alt text](image-17.png)
![alt text](image-18.png)