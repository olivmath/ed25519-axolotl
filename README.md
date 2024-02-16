 # 📦 Ed25519 Axolotl

 Ed25519-like signatures with X25519 keys, Axolotl-style.

 ## ⚠️ Caution

 This repository is full of cryptography functions with some abstraction, be sure what you are doing

 ## 🔭 Telescope

 For the user guide and further documentation, please read
 [Telescope](https://blockchain.lunes.io/telescope)

 ## 🏗 Archtecture

 - **Utils**
     - random
         - random_bytes *usize* -> *Vec<u32>*
     - extras
         - ...
 - **Crypto**
     - keys
         - KeyPair::new *Option<Vec<u32>>* -> *KeyPair*
             - prvk -> *Vec<u32>*
             - pubk -> *Vec<u32>*
     - signatures


## Credits

Curve25519 signatures (and also key agreement) like in the early Axolotl.
Ported to Rust by Miguel Sandro Lucero. miguel.sandro@gmail.com. 2021.09.11

You can use it under MIT or CC0 license.

Curve25519 signatures idea and math by Trevor Perrin
https://moderncrypto.org/mail-archive/curves/2014/000205.html
Derived from axlsign.js written by Dmitry Chestnykh. https://github.com/wavesplatform/curve25519-js
