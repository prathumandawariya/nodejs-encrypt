cryptoutil

The cryptoutil module in Node.js provides cryptographic functionality including hash functions, HMAC, cipher, decipher, sign, verify, and more. 

Features :

1. Hash functions for creating message digests.
2. HMAC (Hash-based Message Authentication Code) for message integrity verification.
3. Cipher and decipher functions for encryption and decryption.
4. Sign and verify functions for digital signatures.
5. Random number generation.
6. Utility functions for working with binary data.


Usage :

To use the cryptoutil module in your Node.js application, simply require it:

javascript -> const crypto = require('cryptoutil');

Once imported, you can use the various cryptographic functions provided by the module. Here are a few examples:


const CryptoUtil = require('./crypto-util');

var plainText = "Testing CryptoJS";

console.log(CryptoUtil.encrypt(plainText)); // Output -> 'UwLMfYsbOIvGSwbjY3SHoAcPkPKPOim6tnH0JPfUFdU='

console.log(CryptoUtil.decrypt('UwLMfYsbOIvGSwbjY3SHoAcPkPKPOim6tnH0JPfUFdU='));  // Output -> 'Testing CryptoJS'

