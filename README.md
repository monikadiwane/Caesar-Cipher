# Caesar-Cipher
In Cryptography, a caesar cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet..

### Example

The transformation can be represented by aligning two alphabets; the cipher alphabet is the plain alphabet rotated left or right by some number of positions. For instance, here is a Caesar cipher using a left rotation of three places, equivalent to a right shift of 23 (the shift parameter is used as the key):

![image](https://user-images.githubusercontent.com/44876424/215147953-720f2c8a-e47d-4b41-8451-ad844d18ca42.png)

When encrypting, a person looks up each letter of the message in the "plain" line and writes down the corresponding letter in the "cipher" line.

![image](https://user-images.githubusercontent.com/44876424/215148078-c9903a17-674b-4b26-bd40-8e410c0b6110.png)

Deciphering is done in reverse, with a right shift of 3.

### Sample Output
* encoding the message

![image](https://user-images.githubusercontent.com/44876424/215148485-6562357b-d664-45a2-a903-22032fa1a1d0.png)

* decoding the message

![image](https://user-images.githubusercontent.com/44876424/215148869-f23d5fa0-183e-4e7c-b56d-4db41215eb46.png)

* encoding with shift greater than 26
![image](https://user-images.githubusercontent.com/44876424/215149529-ecf7e1e0-fb62-435d-bb68-bffe58d97bb5.png)

*decoding with shift greater than 26
![image](https://user-images.githubusercontent.com/44876424/215149727-aaa1d13f-c01b-4fac-af75-a734b2cd35dd.png)
