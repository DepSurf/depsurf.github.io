# Function: <code>crypto_cipher_decrypt_one</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583040499,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1533",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583094559,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1533",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583261087,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1581",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583468420,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1594",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583590397,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1779",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583778414,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583880158,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584216096,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:86",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584216096,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334464,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:86",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334464,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369008,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:87",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369008,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764176,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:87",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764176,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447376,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:87",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447376,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205456,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:87",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205456,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586443744,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:87",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443744,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586709600,
      "name": "crypto_cipher_decrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:87",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709600,
      "name": "crypto_cipher_decrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495698556,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229052908,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289845704,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274848598,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583848894,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583785950,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583832654,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
  "name": "crypto_cipher_decrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583933726,
      "name": "crypto_cipher_decrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1776",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_decrypt",
        "crypto/cbc.c:crypto_cbc_decrypt"
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
void crypto_cipher_decrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
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
