# cryptopals

Solutions and notes for the [Cryptopals crypto challenges](https://cryptopals.com/).

> ⚠️ **Spoilers.** This repository contains full solutions. If you plan to work through the challenges yourself, try them first.

## About

Cryptopals is a set of 66 exercises, originally known as the Matasano crypto challenges. They walk through real-world attacks on cryptography: XOR and block cipher modes, padding oracles, length extension, timing leaks, Diffie-Hellman, RSA, DSA and elliptic curves. The point is to build each attack yourself instead of just reading about it.

## Repository layout

```
cryptopals/
├── lib/            shared primitives reused across sets (XOR, padding, block modes, ...)
├── set1/ ... set8/ solutions, one per challenge
└── notes/          write-ups and other additional materials
```

## Progress

| Set | Topic | Challenges | Done |
|:---:|-------|:----------:|:----:|
| [1](https://cryptopals.com/sets/1) | Basics | 1–8 | 0/8 |
| [2](https://cryptopals.com/sets/2) | Block crypto | 9–16 | 0/8 |
| [3](https://cryptopals.com/sets/3) | Block & stream crypto | 17–24 | 0/8 |
| [4](https://cryptopals.com/sets/4) | Stream crypto and randomness | 25–32 | 0/8 |
| [5](https://cryptopals.com/sets/5) | Diffie-Hellman and friends | 33–40 | 0/8 |
| [6](https://cryptopals.com/sets/6) | RSA and DSA | 41–48 | 0/8 |
| [7](https://cryptopals.com/sets/7) | Hashes | 49–56 | 0/8 |
| [8](https://cryptopals.com/sets/8) | Abstract algebra | 57–66 | 0/10 |

<details>
<summary><b>Set 1 — Basics</b></summary>

- [ ] 1. Convert hex to base64
- [ ] 2. Fixed XOR
- [ ] 3. Single-byte XOR cipher
- [ ] 4. Detect single-character XOR
- [ ] 5. Implement repeating-key XOR
- [ ] 6. Break repeating-key XOR
- [ ] 7. AES in ECB mode
- [ ] 8. Detect AES in ECB mode

</details>

<details>
<summary><b>Set 2 — Block crypto</b></summary>

- [ ] 9. Implement PKCS#7 padding
- [ ] 10. Implement CBC mode
- [ ] 11. An ECB/CBC detection oracle
- [ ] 12. Byte-at-a-time ECB decryption (Simple)
- [ ] 13. ECB cut-and-paste
- [ ] 14. Byte-at-a-time ECB decryption (Harder)
- [ ] 15. PKCS#7 padding validation
- [ ] 16. CBC bitflipping attacks

</details>

<details>
<summary><b>Set 3 — Block & stream crypto</b></summary>

- [ ] 17. The CBC padding oracle
- [ ] 18. Implement CTR, the stream cipher mode
- [ ] 19. Break fixed-nonce CTR mode using substitutions
- [ ] 20. Break fixed-nonce CTR statistically
- [ ] 21. Implement the MT19937 Mersenne Twister RNG
- [ ] 22. Crack an MT19937 seed
- [ ] 23. Clone an MT19937 RNG from its output
- [ ] 24. Create the MT19937 stream cipher and break it

</details>

<details>
<summary><b>Set 4 — Stream crypto and randomness</b></summary>

- [ ] 25. Break "random access read/write" AES CTR
- [ ] 26. CTR bitflipping
- [ ] 27. Recover the key from CBC with IV=Key
- [ ] 28. Implement a SHA-1 keyed MAC
- [ ] 29. Break a SHA-1 keyed MAC using length extension
- [ ] 30. Break an MD4 keyed MAC using length extension
- [ ] 31. Implement and break HMAC-SHA1 with an artificial timing leak
- [ ] 32. Break HMAC-SHA1 with a slightly less artificial timing leak

</details>

<details>
<summary><b>Set 5 — Diffie-Hellman and friends</b></summary>

- [ ] 33. Implement Diffie-Hellman
- [ ] 34. Implement a MITM key-fixing attack on Diffie-Hellman with parameter injection
- [ ] 35. Implement DH with negotiated groups, and break with malicious "g" parameters
- [ ] 36. Implement Secure Remote Password (SRP)
- [ ] 37. Break SRP with a zero key
- [ ] 38. Offline dictionary attack on simplified SRP
- [ ] 39. Implement RSA
- [ ] 40. Implement an E=3 RSA Broadcast attack

</details>

<details>
<summary><b>Set 6 — RSA and DSA</b></summary>

- [ ] 41. Implement unpadded message recovery oracle
- [ ] 42. Bleichenbacher's e=3 RSA Attack
- [ ] 43. DSA key recovery from nonce
- [ ] 44. DSA nonce recovery from repeated nonce
- [ ] 45. DSA parameter tampering
- [ ] 46. RSA parity oracle
- [ ] 47. Bleichenbacher's PKCS 1.5 Padding Oracle (Simple Case)
- [ ] 48. Bleichenbacher's PKCS 1.5 Padding Oracle (Complete Case)

</details>

<details>
<summary><b>Set 7 — Hashes</b></summary>

- [ ] 49. CBC-MAC Message Forgery
- [ ] 50. Hashing with CBC-MAC
- [ ] 51. Compression Ratio Side-Channel Attacks
- [ ] 52. Iterated Hash Function Multicollisions
- [ ] 53. Kelsey and Schneier's Expandable Messages
- [ ] 54. Kelsey and Kohno's Nostradamus Attack
- [ ] 55. MD4 Collisions
- [ ] 56. RC4 Single-Byte Biases

</details>

<details>
<summary><b>Set 8 — Abstract algebra</b></summary>

- [ ] 57. Diffie-Hellman Revisited: Small Subgroup Confinement
- [ ] 58. Pollard's Method for Catching Kangaroos
- [ ] 59. Elliptic Curve Diffie-Hellman and Invalid-Curve Attacks
- [ ] 60. Single-Coordinate Ladders and Insecure Twists
- [ ] 61. Duplicate-Signature Key Selection in ECDSA (and RSA)
- [ ] 62. Key-Recovery Attacks on ECDSA with Biased Nonces
- [ ] 63. Key-Recovery Attacks on GCM with Repeated Nonces
- [ ] 64. Key-Recovery Attacks on GCM with a Truncated MAC
- [ ] 65. Truncated-MAC GCM Revisited: Improving the Key-Recovery Attack via Ciphertext Length Extension
- [ ] 66. Exploiting Implementation Errors in Diffie-Hellman

</details>

## Credits

Challenges created by the Cryptopals team, originally at Matasano Security. All solutions and notes in this repository are my own.
