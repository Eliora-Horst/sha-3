# SHA-3 et al.
## Graduate Project 1: The Paper
### Eliora Horst
### COMP 447: Intrusion Detection & Security
### Dr. Corby Schmitz
### Loyola University Chicago

## Introduction
While there are countless algorithms used to secure the movement of data across networks, hashing algorithms are the only variety that serve as the digital fingerprints of the network security world.  Hashing algorithms achieve this by providing complex, one-way mappings, that make a totally unique hashed message that cannot be reverse engineered to reveal the original data.  They are also useful for digital signatures, message authentication codes (MACs), key derivation functions, pseudo random functions, and a variety of other security applications.~1~   Hashes are useful for providing authentication of data, and for ensuring data remained unchanged through travel and outside manipulation.  The key to hashing, in terms of security, is that every hash is distinct.  Every generated digest is unique, and even the smallest of changes to the original data can result in digests that barely resemble the previous iteration.
![Sha-3 Example](sha-3-example.png)
SHA-3 is the latest iteration of this hashing technology.  Released in 2015, it makes significant improvements to previous versions of the SHA family of hashing algorithms, particularly in regards to collisions.  Its internal structure is also significantly different, compared to SHA-1 and SHA-2.  It currently utilizes Keccak algorithm, which allows for both variable sized input and output.  As of September 2020, there have been no fatal flaws discovered, or any vulnerabilities that could lead to collisions.
