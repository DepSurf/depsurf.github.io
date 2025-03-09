# Function: <code>crypto_skcipher_setkey</code>

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
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581508030,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232607,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238387,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582431144,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582442509,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582938962,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943308,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964707,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581593342,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582322099,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327875,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582523336,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534701,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583040898,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044458,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583047260,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069219,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:364",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581653357,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406867,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413269,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582606952,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582618271,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583094914,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098362,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101607,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124139,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581797934,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557587,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563925,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771887,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583261458,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583264959,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268471,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583277984,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298139,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581972939,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582749411,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755505,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582972147,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583469167,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472402,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583475686,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485283,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506602,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:398",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582060319,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853203,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582859377,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083331,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583591151,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594978,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583596614,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583601457,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583630394,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:435",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582221901,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583027955,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583034075,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268307,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583779173,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782646,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583783638,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583788926,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815146,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:370",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308184,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311515,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134164,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140299,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583374227,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583880917,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583885558,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583886550,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891870,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916762,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584229632,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:599",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229632,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348096,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:599",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348096,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584382288,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:594",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382288,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777520,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:594",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777520,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585463968,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:594",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585463968,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586223568,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:594",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223568,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586459152,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:612",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459152,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730208,
      "name": "crypto_skcipher_setkey",
      "external": true,
      "loc": "crypto/skcipher.c:616",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/cts.c:crypto_cts_setkey",
        "crypto/ctr.c:crypto_rfc3686_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_evict",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_keyslot_program"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730208,
      "name": "crypto_skcipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493885784,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493889132,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494844964,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494850556,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495123260,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495699340,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495704828,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495705100,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495711876,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495737364,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227366504,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 3227370324,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228263632,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_extent"
      ],
      "caller_func": []
    },
    {
      "addr": 3228268868,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 3228511656,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229053272,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 3229058816,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229059036,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 3229066600,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 3229087812,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287520936,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287525648,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288695432,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288703052,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289030748,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289846712,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289853068,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289854448,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289862868,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289892928,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273447024,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273450284,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274167030,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274172332,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274376750,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274849168,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274853078,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274854098,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274859480,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274887234,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582276920,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280251,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583102900,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109035,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583342963,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583849653,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583854294,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583855286,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583860606,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583885498,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582214680,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582218011,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040052,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046187,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583280067,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583786709,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791350,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583792342,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797662,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583822554,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582267400,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270731,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583091508,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097643,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583326739,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583833413,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583838054,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583839046,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844366,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583869258,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_skcipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582345960,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349291,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/crypto/keysetup_v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup_v1.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583180724,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583186843,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583421763,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583934485,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939126,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583940118,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945438,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583970330,
      "name": "crypto_skcipher_setkey",
      "external": false,
      "loc": "include/crypto/skcipher.h:400",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_update",
        "crypto/drbg.c:drbg_ctr_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int crypto_skcipher_setkey(struct crypto_skcipher * tfm, const u8 * key, unsigned int keylen)
```
</details>
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
