# Password-manager
The point of this program is to organise or store the passwords along with the username or the account they are associated within the text file. We are going to encrypt the passwords which means we need another password to decrypt them which is our Master Password. We have used cryptography Fernet module to encrypt it essentially.

We will define the key, so it is going to take a string of text & using a key to turn it into a completely random string of text that we cannot get back to the orignal text without knowing the key. We will combine this key with our master password.
Now if we provide the wrong password and try to decrypt this, then we'll get something that makes no sense. We'll not get the orignal text because we need key and password to get back to the orignal text.

So the master password in combination with the key which we are going to store, we'll be able to encrypt and decrypt the text. If we type the wrong master password we'll get the wrong decrypted result. 

So we need two functions: 1) To create a key, 2) To Retrive the key.
