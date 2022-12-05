Student: Volodymyr Yuziuk 

Group: CE 48 

Subject: CSDT

Project name: Chrome dragon game

HW interface: I2C

Data driven format: JSON

How to run project:
There are two ways to start a project:
1.With connection through SPI (Two Arduino boards are required)
2.Without connection through SPI (One Arduino board is required)

With connection through SPI:
Connect 2 Arduino to PC
Open SPIServer/SPISlave.ino in Arudino IDE and upload script to first Arduino board
Open SPIServer/SPIMaster.ino in Arudino IDE and upload script to second Arduino board
Connect (MOSI, MISO, SCK, SS) pins of the first Arduino with the same pins of the second Arduino board
Change COM Port

Without connection through SPI:
Connect Arduino to PC
Open NotSPIServer/Server.ino in Arudino IDE and upload script to Arduino board
Change COM Port
