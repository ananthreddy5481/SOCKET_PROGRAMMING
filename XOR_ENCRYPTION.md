implementing the XOR encyption for the communication 

<img width="494" height="276" alt="Screenshot 2026-01-21 at 9 25 02 PM" src="https://github.com/user-attachments/assets/82564789-6928-45b0-8c56-905e1f601061" />


making a function for the xor encryption .

encoding the input text if that is a string data.

in the xor encryption we need to do xor operation for the two inputs one will be the input text message and a secret key .

the secret key may be less length of the input message so in that case the key should be repeating for until the length of the input text is xor operated.

for that we use the part 
<img width="494" height="80" alt="Screenshot 2026-01-21 at 9 38 03 PM" src="https://github.com/user-attachments/assets/ee8ad840-8721-4474-a35c-b487a23a00f9" />

here the zip is for making the itreation for both x and y which represents the input text and key like the byte by byte xor operation of the each text and key.

then it returns them .

DECRYTPING :

for decrypting the xor encyption we have to perform the same xor operation again with the same key for the getting the original text message.

for that we have give the same xor encyption and the same key in the client side also.

<img width="494" height="564" alt="Screenshot 2026-01-21 at 9 44 43 PM" src="https://github.com/user-attachments/assets/900f5499-728b-4a21-83f9-375b50957dc7" />

in the line no 13 we can see performing the xor encyption function for obtaining the decrypted message.


<img width="494" height="656" alt="Screenshot 2026-01-21 at 9 46 16 PM" src="https://github.com/user-attachments/assets/a0b24b37-727c-4246-b8ce-651f75bb960d" />

in the server side also we can see that the server is also decrypting the text message that we got from the clent.





