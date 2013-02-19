pecl-xxtea
==========

XXTEA PHP extension


What is it?
-----------
This extension based on xxtea library, which provides a set of functions
for encrypt or decrypt data with XXTEA algorithm.



How to install it?
------------------
See INSTALL for installation instructions.



How to use it?
--------------

-     string xxtea_encrypt(string data, string key)

  Encrypt data using XXTEA algorithm. The key is a 16 bytes(128 bits) string.

-     string xxtea_decrypt(string data, string key)

  Decrypt data using XXTEA algorithm. The key is a 16 bytes(128 bits) string.

-     string xxtea_info()

  Get the version information.