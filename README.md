# CSC852 Security and Data Privacy FinalProject
Analysis of DES, 3DES and AES Algorithm

## Implementation Requirements
Measure and compare the time taken for encryption and decryption using DES, 3DES and AES, with different input sizes. Analyze the three algorithms and identify which component(s) made an algorithm particularly fast/slow, weak/strong.

### Analysis of Encryption and Decryption using DES, 3DES, and AES Algorithm

#### Overview
Data Encryption Standard (DES) and Advanced Encryption Standard (AES) are the symmetric block cipher but both of them including 3DES has some advantages and disadvantages. We know from the definition that DES uses the Feistel network which divides the block into two halves for the process of encryption. Also, DES has a key length of 64 bits which is very small to prevent any kind of brute-force attacks. 3DES is just the 3 times repetitions of the DES algorithm. So in terms of key length and structure, it is similar to the DES algorithm. 

On the other hand, AES has three different key lengths 128 bits, 192 bits, and 256 bits which make this algorithm more strong. AES uses Byte substitution layer and Key addition layer for the process of encryption. 

#### To analyze and compare DES, 3DES, and AES  algorithms the following steps were taken: 
* Measure the time taken for encryption and decryption with eight different input sizes. 
* Compare the average time to see which algorithm is fast or slow.
* Identify the component for which an algorithm is weak or strong. 
* Identify which algorithm provides better security over other algorithms.

#### Procedure
In the coding part for this analysis "Jupyter Notebook" was used to measure time with different input sizes using the DES, 3DES, and AES algorithms from PyCryptodome. This allowed time measurement for each cell.

 In the next stage, time(Micro Second) was plotted for eight different input sizes for each algorithm via Google sheets. For the visual representation bar charts and line, charts were used. The average value has been measured from each chart to have the right insight into the time taken by the algorithms. Below is the list of input sizes of  each algorithm that was executed in Jupyter Notebook: 

* Encryption and Decryption using DES with  inputs 16bits / 32bits / 64bits / 256 bits / 512 bits/ 1024bits/ 2048bits
* Encryption and Decryption using DES with  inputs 16bits / 32bits / 64bits / 256 bits / 512 bits/ 1024bits/ 2048bits
* Encryption and Decryption using 3DES with  input 16bits / 32bits / 64bits / 256 bits / 512 bits/ 1024bits/ 2048bits
* Encryption and Decryption using AES with  key length 128 bits and input 16bits / 32bits / 64bits / 256 bits / 512 bits/ 1024bits/ 2048bits
* Encryption and Decryption using AES with  key length 192 bits and input 16bits / 32bits / 64bits / 256 bits / 512 bits/ 1024bits/ 2048bits
* Encryption and Decryption using AES with  key length 256 bits and input 16bits / 32bits / 64bits / 256 bits / 512 bits/ 1024bits/ 2048bits

> For more details on visual representaion using Google Charts see the "CSC852 Final Project Document" file.