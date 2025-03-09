# Function: <code>crypto_shash_setkey</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659936,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:54",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/shash.c:shash_compat_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659936,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906080,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:54",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906080,
      "name": "crypto_shash_setkey",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005808,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:54",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005808,
      "name": "crypto_shash_setkey",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583056176,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:55",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056176,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583222256,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:56",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583222256,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430224,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:56",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430224,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551616,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:63",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551616,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583740800,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740800,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850560,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850560,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584241664,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:57",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239632,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584360240,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:57",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358144,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584394704,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:69",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392608,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584789936,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:69",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787840,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585476112,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:69",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/kdf_sp800108.c:crypto_kdf108_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585475168,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586237088,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:59",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/kdf_sp800108.c:crypto_kdf108_setkey"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236048,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586474592,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:68",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/kdf_sp800108.c:crypto_kdf108_setkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586471840,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586743792,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:44",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/ahash.c:crypto_ahash_setkey",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/drbg.c:drbg_hmac_update",
        "crypto/kdf_sp800108.c:crypto_kdf108_setkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586743792,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495665384,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495665384,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229018556,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229018556,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289803872,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289803872,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274816732,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274816732,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819296,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819296,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756352,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756352,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583803056,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583803056,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int crypto_shash_setkey(struct crypto_shash * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_shash_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583904096,
      "name": "crypto_shash_setkey",
      "external": true,
      "loc": "crypto/shash.c:58",
      "file": "crypto/shash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf",
        "fs/crypto/hkdf.c:hkdf_extract",
        "security/keys/trusted.c:TSS_rawhmac",
        "security/integrity/evm/evm_crypto.c:init_desc",
        "crypto/shash.c:shash_async_setkey",
        "crypto/drbg.c:drbg_kcapi_hmacsetkey",
        "net/ipv6/seg6_hmac.c:seg6_hmac_compute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904096,
      "name": "crypto_shash_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
