# Function: <code>crypto_alloc_skcipher</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653504,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:239",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653504,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901536,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:336",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/big_key.c:big_key_crypto_init",
        "crypto/crypto_null.c:crypto_get_default_null_skcipher",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901536,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998352,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:878",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/big_key.c:big_key_init",
        "crypto/crypto_null.c:crypto_get_default_null_skcipher",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998352,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048416,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:918",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/big_key.c:big_key_init",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/crypto_null.c:crypto_get_default_null_skcipher",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048416,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213904,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:924",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/crypto_null.c:crypto_get_default_null_skcipher",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213904,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422112,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:947",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/crypto_null.c:crypto_get_default_null_skcipher",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422112,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543072,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:951",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543072,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731584,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:985",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731584,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841248,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841248,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584230320,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:758",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584230320,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348912,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:758",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348912,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584383072,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:753",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383072,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778304,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:753",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778304,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585463232,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:753",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585463232,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586222112,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:753",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222112,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586457712,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:800",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457712,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728800,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:899",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728800,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495654304,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495654304,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229008628,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229008628,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289789840,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289789840,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274807220,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274807220,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809984,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809984,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747040,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747040,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793744,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793744,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
struct crypto_skcipher * crypto_alloc_skcipher(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_skcipher",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894832,
      "name": "crypto_alloc_skcipher",
      "external": true,
      "loc": "crypto/skcipher.c:989",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/keysetup.c:fscrypt_allocate_skcipher",
        "fs/crypto/keysetup_v1.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx",
        "security/keys/encrypted-keys/encrypted.c:init_encrypted",
        "crypto/drbg.c:drbg_init_sym_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894832,
      "name": "crypto_alloc_skcipher",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
