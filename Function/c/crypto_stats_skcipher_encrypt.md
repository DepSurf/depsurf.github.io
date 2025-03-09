# Function: <code>crypto_stats_skcipher_encrypt</code>

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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1285",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/crypto.c:fscrypt_do_page_crypto",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/fname.c:fname_encrypt",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/crypto/keyinfo.c:derive_key_aes",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/crypto.c:crypt_scatterlist",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:write_tag_3_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/seqiv.c:seqiv_aead_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:crypto_cts_encrypt",
        "crypto/cts.c:cts_cbc_encrypt",
        "crypto/ctr.c:crypto_rfc3686_crypt",
        "crypto/gcm.c:crypto_rfc4543_copy_src_to_dst",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_encrypt",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/gcm.c:crypto_gcm_setkey",
        "crypto/drbg.c:drbg_kcapi_sym_ctr",
        "crypto/drbg.c:drbg_kcapi_sym_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583530880,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583719312,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1254",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583719312,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583829056,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829056,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584224464,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1236",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224464,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342208,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1255",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342208,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1255",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584376624,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1237",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772640,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1279",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456992,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1227",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215088,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495637488,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228994652,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289758800,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289758800,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274794878,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583797792,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583797792,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734848,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734848,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781552,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781552,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
```

```json
{
  "name": "crypto_stats_skcipher_encrypt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583882544,
      "name": "crypto_stats_skcipher_encrypt",
      "external": true,
      "loc": "crypto/algapi.c:1264",
      "file": "crypto/algapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:crypto_skcipher_encrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583882544,
      "name": "crypto_stats_skcipher_encrypt",
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg * alg)
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
