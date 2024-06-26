# NetPractice
> This repository contains a "NetPractice" project that is part of the École 42 curriculum.

 NetPractice is a general practical exercise to let you discover networking and subnetting.

 <div align="center">
  <img src="https://github.com/MofMiq/NetPractice/blob/main/imgs/level4.png" width="600"/>
</div>

## Usage
1. There are 10 levels available for training.
2. Complete the empty fields and click on button `Check again` to verify whether your configuration is correct or not.
3. Once the exercise is successful, click on button `Get my config` to download your configuration.
4. When you have successfully completed a level, click on button `Next level`.

## Basics
### What is IP?
An IP (Internet Protocol) address is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication.
An IP address serves two main functions:
1. **Host or Network Interface Identification**: It uniquely identifies a device on a local network or the internet.
2. **Location Addressing**: It provides the location of the device within the network, enabling data to be routed to and from it accurately.
IP addresses are of two types:
1. **IPv4**: Uses a 32-bit address scheme allowing for approximately 4.3 billion unique addresses. It is represented in decimal format as four octets separated by periods (e.g., 192.168.0.1).
2. **IPv6**: Uses a 128-bit address scheme, vastly increasing the number of available addresses. It is represented in hexadecimal format, separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

 <div align="center">
  <img src="https://github.com/MofMiq/NetPractice/blob/main/imgs/network.png" width="600"/>
</div>

### What is Subnet Mask?
A subnet mask is a 32-bit number created by setting host bits to all 0s and setting network bits to all 1s. In this way, the subnet mask separates the IP address into the network and host addresses.

The “255” address is always assigned to a broadcast address, and the “0” address is always assigned to a network address. Neither can be assigned to hosts, as they are reserved for these special purposes.

### Subnet Mask Chart
Here is a quick reference table for help when subnetting.
|Subnet Mask 	|CIDR |	Binary Notation| 	Network Bits| 	Host Bits| 	Available Addresses|
| -           | -   | -              | -            | -          | -                   | 
|255.255.255.255| 	/32| 	11111111.11111111.11111111.11111111| 	32| 	0| 	1|
|255.255.255.254| 	/31| 	11111111.11111111.11111111.11111110| 	31| 	1| 	2|
|255.255.255.252| 	/30| 	11111111.11111111.11111111.11111100| 	30| 	2| 	4|
|255.255.255.248| 	/29| 	11111111.11111111.11111111.11111000| 	29| 	3| 	8|
|255.255.255.240| 	/28| 	11111111.11111111.11111111.11110000| 	28| 	4| 	16|
|255.255.255.224| 	/27| 	11111111.11111111.11111111.11100000| 	27| 	5| 	32|
|255.255.255.192| 	/26| 	11111111.11111111.11111111.11000000| 	26| 	6| 	64|
|255.255.255.128| 	/25|     11111111.11111111.11111111.10000000| 	25| 	7| 	128|
|255.255.255.0| 	/24| 	11111111.11111111.11111111.00000000| 	24| 	8| 	256|		
|255.255.254.0| 	/23| 	11111111.11111111.11111110.00000000| 	23| 	9| 	512|
|255.255.252.0| 	/22| 	11111111.11111111.11111100.00000000| 	22| 	10| 	1024|
|255.255.248.0| 	/21| 	11111111.11111111.11111000.00000000| 	21| 	11| 	2048|
|255.255.240.0| 	/20| 	11111111.11111111.11110000.00000000| 	20| 	12| 	4096|
|255.255.224.0| 	/19| 	11111111.11111111.11100000.00000000| 	19| 	13| 	8192|
|255.255.192.0| 	/18| 	11111111.11111111.11000000.00000000| 	18| 	14| 	16384|
|255.255.128.0| 	/17| 	11111111.11111111.10000000.00000000| 	17| 	15| 	32768|
|255.255.0.0| 	/16| 	11111111.11111111.00000000.00000000| 	16| 	16| 	65536|	
|255.254.0.0| 	/15| 	11111111.11111110.00000000.00000000| 	15| 	17| 	131072|
|255.252.0.0| 	/14| 	11111111.11111100.00000000.00000000| 	14| 	18| 	262144|
|255.248.0.0| 	/13| 	11111111.11111000.00000000.00000000| 	13| 	19| 	524288|
|255.240.0.0| 	/12| 	11111111.11110000.00000000.00000000| 	12| 	20| 	1048576|
|255.224.0.0| 	/11| 	11111111.11100000.00000000.00000000| 	11| 	21| 	2097152|
|255.192.0.0| 	/10| 	11111111.11000000.00000000.00000000| 	10| 	22| 	4194304|
|255.128.0.0| 	/9| 	11111111.10000000.00000000.00000000| 	9| 	23| 	8388608|
|255.0.0.0| 	    /8| 	11111111.00000000.00000000.00000000| 	8| 	24| 	16777216| 


Here is an example of the most compex level of the project:
 <div align="center">
  <img src="https://github.com/MofMiq/NetPractice/blob/main/imgs/level9.png" width="600"/>
</div>
