# Function: <code>crypto_skcipher_encrypt</code>

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
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581502100,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581504310,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581508130,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582225926,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238537,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582431351,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582443110,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582902690,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940380,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943477,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955753,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
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
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581587137,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581589598,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593442,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315430,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582328025,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582523543,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582536963,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583002434,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042316,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583046956,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047429,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060065,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:407",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
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
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581647923,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649588,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653443,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400097,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413421,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607152,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "security/keys/big_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/big_key.c:big_key_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582620660,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583052613,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095486,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101140,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101781,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115295,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
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
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581793345,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794942,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581798025,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551020,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582564080,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774212,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583218229,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583262046,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267768,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268645,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273020,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583289261,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:441",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
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
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581967746,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970077,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973032,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743183,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755685,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582973761,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583426368,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583469742,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474940,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:do_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475837,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583478601,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_crypt",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497572,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:436",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
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
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582054498,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582057044,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "fs/crypto/fname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/fname.c:fname_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060421,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keyinfo.c:derive_key_aes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846955,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:crypt_scatterlist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582859564,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "fs/ecryptfs/keystore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085731,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "security/keys/encrypted-keys/encrypted.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583547433,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "crypto/seqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/seqiv.c:seqiv_aead_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583592621,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "crypto/cts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583596030,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583596782,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_rfc3686_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583602119,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629554,
      "name": "crypto_skcipher_encrypt",
      "external": false,
      "loc": "include/crypto/skcipher.h:487",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730432,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:840",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730432,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840096,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840096,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584229728,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:624",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229728,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348192,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:624",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348192,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584382384,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:619",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382384,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777616,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:619",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777616,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585462544,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:619",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462544,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586221376,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:619",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586221376,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586459504,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:637",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459504,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730656,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:653",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_data_unit",
        "fs/crypto/fname.c:fscrypt_fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730656,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495652832,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495652832,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229007332,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/ecryptfs/crypto.c:crypt_extent",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229007332,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289787904,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289787904,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274805914,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274805914,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583808832,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583808832,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745888,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745888,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583792592,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792592,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
```

```json
{
  "name": "crypto_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583893680,
      "name": "crypto_skcipher_encrypt",
      "external": true,
      "loc": "crypto/skcipher.c:844",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_crypt_block",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893680,
      "name": "crypto_skcipher_encrypt",
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
int crypto_skcipher_encrypt(struct skcipher_request * req)
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
