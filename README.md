# CaesarCipher
 Also known as Caesar's cipher, the shift cipher, Caesar's code or Caesar shift
 
# Introduction

The Caesar Cipher is one of the oldest and simplest forms of encrypting a message. It is a type of substitution cipher where each letter in the original message (which in cryptography is called the plaintext) is replaced with a letter corresponding to a certain number of letters shifted up or down in the alphabet. 

<img src="https://learncryptography.com/assets/content/images/caesar_cipher.jpg" align="middle" alt="CaesarCipher" width="550" height="350" >

### Running (Encipher & Decipher)
```
$ python3 CaesarCipher.py
	>>> encipher('hello', 1)
	   'ifmmp'
	>>> encipher('hello', 2)
	   'jgnnq'
	>>> encipher('hello', 4)
	   'lipps'
 >>> rot('a', 1)
    'b'
 >>> print(rot('a', 1))
    	b
	>>> rot('y', 2)
    'a'
	>>> rot('A', 3)
   	'D'
	>>> rot('Y', 3)
   	'B'
	>>> rot('!', 4)
   	'!'
 >>> encipher('xyza', 1)
    'yzab'
>>> encipher('Z A', 2)
    'B C'
>>> encipher('Caesar cipher? I prefer Caesar salad.', 25)
    'Bzdrzq bhogdq? H oqdedq Bzdrzq rzkzc.'
>>> decipher('Bzdrzq bhogdq? H oqdedq Bzdrzq rzkzc.')
   	'Caesar cipher? I prefer Caesar salad.'
>>> decipher('Hu lkbjhapvu pz doha ylthpuz hmaly dl mvynla lclyfaopun dl ohcl slhyulk.')
   'An education is what remains after we forget everything we have learned.'
>>> decipher('python')
    'eniwdc'

```

### Requirements
Python 3

