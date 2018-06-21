# RSA-implementation

RSA (Rivest–Shamir–Adleman) is a public-key cryptosystems

A user of RSA creates and then publishes a public key based on two large prime numbers, along with an auxiliary value. The prime numbers must be kept secret. Anyone can use the public key to encrypt a message, but with currently published methods, and if the public key is large enough, only someone with knowledge of the prime numbers can decode the message feasibly.

Breaking RSA encryption is known as the RSA problem. Whether it is as difficult as the factoring problem remains an open question.

---
# How to use
`python rsa.py`

# Example
```console
RSA Encrypter/ Decrypter   
Enter a prime number (17, 19, 23, etc): 17    
Enter another prime number (Not one you entered above): 19   
Generating your public/private keypairs now . . .    
Your public key is  (157, 323)  and your private key is  (277, 323)   
Enter a message to encrypt with your private key: HelloWorld!   
Your encrypted message is:
89237143143934993190143206288  
Decrypting message with public key  (157, 323)  . . .
Your message is:  
HelloWorld!
```

# Reminder
A couple of prime number you could test:
```console
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47,53, 59, 61, 67, 71, 73, 79, 83, 89, 97,
101, 103, 107, 109, 113, 127, 131, 137, 139, 149, 151, 157, 163, 167, 173, 179, 181, 191, 193
```
