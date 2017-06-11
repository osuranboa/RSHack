# RSHack for CTF

## About

* This tool written in python allows to carry out one of the available attacks on RSA in this repository:

	* Wiener Attack
	* Hastad Attack
	* Fermat Attack
	* Bleichenbacher Attack
	* Common Modulus Attack
	* Chosen Plaintext Attack

* Some other features are implented:

	* RSA Public Key parameters extraction
	* RSA Private Key construction (PEM)
	* RSA Public Key construction (PEM)
	* RSA Ciphertext Decipher
	* RSA Ciphertext Encipher
	
* More informations: https://zweisamkeit.fr/rshack/ (fr)

## Requirements

* Python 2.7 / 3.6
	
	* PyCrypto
	* gmpy2

## Todo

* More attacks (Discrete logarithm, factorization...)
* Python 3 only
* GUI? (v3.0)

## Releases

* Version 2.0 - Saturday, 10 June 2017

	* full POO
	* Multiplateform

## Overview

```
		~~~~~~~~~~~~~~~~~~~~~~~~~
		       RSHack v2.0
		       Zweisamkeit
		        GNU GPL v3
		~~~~~~~~~~~~~~~~~~~~~~~~~



	List of the available attacks:

		1. Wiener Attack
		2. Hastad Attack
		3. Fermat Attack
		4. Bleichenbacher Attack
		5. Common Modulus Attack
		6. Chosen Plaintext Attack

	List of the available tools:

		a. RSA Public Key parameters extraction
		b. RSA Private Key construction (PEM)
		c. RSA Public Key construction (PEM)
		d. RSA Ciphertext Decipher
		e. RSA Ciphertext Encipher

	[*] What attack or tool do you want to carry out?

```
