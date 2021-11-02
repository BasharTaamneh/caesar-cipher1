# Cryptography

## Description

* This Module has
-  encrypt function that takes in a plain text phrase and a numeric shift.

- decrypt function that takes in encrypted text and numeric shift which will restore the encrypted text back to its original form when correct key is supplied.

- crack function that will decode the cipher so that an encrypted message can be transformed into its original state WITHOUT access to the key.

## mplementation Notes

- In order to accomplish a certain task we will need access to a corpus of English words.
- A search on something like python list of english words should get us going.

## User Acceptance Tests

> [x] encrypt a string with a given shift.

> [x] decrypt a previously encrypted string with the same shift.

> [x] encryption should handle upper and lower case letters.

> [x] encryption should allow non-alpha characters but ignore them, including white space.

> [x] decrypt encrypted version of It was the best of times, it was the worst of times. WITHOUT knowing the shift used.


## Change log

- Cryptography v1 completed class-18" 02-11-2021


- [PR1](https://github.com/BasharTaamneh/caesar-cipher1/pull/1)