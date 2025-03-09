# Function: <code>hkdf_extract</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299792,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071582300999,
      "name": "hkdf_extract.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582585036,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582655788,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582684844,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583010540,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:48",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583481003,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:48",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584075691,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:48",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584302347,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:48",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584519371,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:48",
      "file": "fs/crypto/hkdf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493875368,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493875368,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227357644,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227357644,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287508896,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287508896,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273439356,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273439356,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582268528,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071582269735,
      "name": "hkdf_extract.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206288,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071582207495,
      "name": "hkdf_extract.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259008,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071582260215,
      "name": "hkdf_extract.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```

```json
{
  "name": "hkdf_extract",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hkdf_extract",
      "external": false,
      "loc": "fs/crypto/hkdf.c:43",
      "file": "fs/crypto/hkdf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/hkdf.c:fscrypt_init_hkdf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582337600,
      "name": "hkdf_extract",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071582338807,
      "name": "hkdf_extract.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int hkdf_extract(struct crypto_shash * hmac_tfm, const u8 * ikm, unsigned int ikmlen, u8 * prk)
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
