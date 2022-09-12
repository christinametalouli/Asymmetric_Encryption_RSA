# Asymmetric_Encryption_RSA
Encryption using the asymmetric algorithm RSA, create a message and sending it from A to B, in kali linux (openssl)


Using openssl we are going to implement an asymmetric encryption rsa, with key generator. 

What we will do? 

We will create a puplic and a private key for both A and B. Then we will create a message in A. We will send to A the public key of B and to B the puplic key of A. Then, we encrypt the message with the puplic key of B and we send the encrypted message to B. B will receive the message and decrypt it using his pivate key. 

The asymmetric encryption procedure you can use if you want to send a message from B to A.



Note:
1) We will use a 2048 bit file.
2) I have tso files, the terminal of A and B. Be careful we don't write A script firts and then B, we are doing it the SAME time.
