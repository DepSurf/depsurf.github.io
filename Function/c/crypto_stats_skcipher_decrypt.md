# Function: <code>crypto_stats_skcipher_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1298",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:crypto_cts_decrypt",
        "crypto/cts.c:cts_cbc_decrypt",
        "crypto/gcm.c:gcm_dec_hash_continue",
        "crypto/gcm.c:gcm_dec_hash_continue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531376,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583719504,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1267",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583719504,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828384,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828384,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223680,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1249",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223680,
      "name": "crypto_stats_skcipher_decrypt",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342544,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1268",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342544,
      "name": "crypto_stats_skcipher_decrypt",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1268",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377184,
      "name": "crypto_stats_skcipher_decrypt",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1250",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772528,
      "name": "crypto_stats_skcipher_decrypt",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1292",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456672,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1240",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586214736,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495638384,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228995300,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289770864,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289770864,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274795092,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583797120,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583797120,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734176,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734176,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780880,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780880,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_decrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881872,
      "name": "crypto_stats_skcipher_decrypt",
      "external": true,
      "loc": "crypto/algapi.c:1277",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881872,
      "name": "crypto_stats_skcipher_decrypt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```
</details>
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
