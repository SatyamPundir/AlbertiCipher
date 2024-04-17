# Alberti Cipher

### Background: 
The Alberti Cipher is the first instance of a polyalphabetic cipher. Created in 1467 by Leon Battista Alberti, the cipher is best simplified through Alberti's disks, which are traditionally two metal disks with 24 cells each holding numbers/letters of the Latin alphabet. In this version of the Alberti Cipher, we made a slight variation, creating 26 cells with the English alphabet in each, while also giving users the ability to create their own version of the cipher.  

In both versions of the cipher, you must choose any letter from A-Z (denoted the outer_disk_key) that will be used to align with every random rotation of the inner disk. This random rotation occurs every period_length letters. 

### To use the regular cipher encoder/decoder:
`make run ARGS="encode/decode text outer_disk_key period_length"`  
Example: make run ARGS="encode helloworld F 5"
