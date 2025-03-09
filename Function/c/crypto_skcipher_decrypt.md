# Function: <code>crypto_skcipher_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581502053,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581505745,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582225954,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582235798,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582431364,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443727,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582939669,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581587090,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581590929,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315458,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582325286,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582523556,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582536348,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583041605,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046668,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:425",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_decrypt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581647862,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651031,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400130,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410086,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607165,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582620056,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583097017,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100836,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_decrypt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581793428,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581796353,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551026,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560737,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582773608,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583263593,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267448,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273786,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:459",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_dec_hash_continue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581967651,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581969262,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582743106,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582752998,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582974462,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583471494,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474588,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481031,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:457",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_dec_hash_continue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582054614,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582056186,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582846822,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856855,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085088,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583593662,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594686,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583601209,
      "name": "crypto_skcipher_decrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:514",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:gcm_dec_hash_continue"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730528,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:857",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730528,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840192,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840192,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584229824,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:641",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229824,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348288,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:641",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:xts_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348288,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584382480,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:636",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:xts_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382480,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777712,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:636",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:xts_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777712,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585462656,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:636",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:xts_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462656,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586221504,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:636",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:xts_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221504,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586459616,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:659",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:xts_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459616,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730800,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:677",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/xts.c:xts_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730800,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495652952,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495652952,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229007436,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_decrypt",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229007436,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289788096,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289788096,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274806020,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274806020,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583808928,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808928,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745984,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745984,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792688,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792688,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583893776,
      "name": "crypto_skcipher_decrypt",
      "external": true,
      "loc": "crypto/skcipher.c:861",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893776,
      "name": "crypto_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request * req)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
