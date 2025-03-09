# Function: <code>crypto_cipher_setkey</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582682734,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1541",
      "file": "crypto/ecb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ecb.c:crypto_ecb_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582683582,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1541",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586719562,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1541",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582936639,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1498",
      "file": "crypto/ecb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ecb.c:crypto_ecb_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937471,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1498",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582941409,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1498",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:setkey",
        "crypto/xts.c:setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943215,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1498",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962427,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1498",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587167706,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1498",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583038447,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/ecb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ecb.c:crypto_ecb_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039280,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044351,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583047167,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066939,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587366890,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581654997,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583092447,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/ecb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ecb.c:crypto_ecb_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093312,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098300,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583101423,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583122360,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587499258,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1501",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581799609,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1549",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583258943,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1549",
      "file": "crypto/ecb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ecb.c:crypto_ecb_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259824,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1549",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583264892,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1549",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583268063,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1549",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296357,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1549",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588021595,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1549",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581974259,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1562",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583466715,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1562",
      "file": "crypto/ecb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ecb.c:crypto_ecb_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583467596,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1562",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472335,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1562",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583475275,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1562",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583504912,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1562",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588372651,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1562",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582062406,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1747",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583588683,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1747",
      "file": "crypto/ecb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ecb.c:crypto_ecb_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583589564,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1747",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583594911,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1747",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583596203,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1747",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583624096,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1747",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588563019,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1747",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582222868,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keyinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583729826,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782579,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583810810,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308746,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839490,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583885491,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583912330,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584216032,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584216032,
      "name": "crypto_cipher_setkey",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334400,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:42",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334400,
      "name": "crypto_cipher_setkey",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368944,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:43",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368944,
      "name": "crypto_cipher_setkey",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764112,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:43",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764112,
      "name": "crypto_cipher_setkey",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447040,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:43",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447040,
      "name": "crypto_cipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205712,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:43",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205712,
      "name": "crypto_cipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586444000,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:43",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444000,
      "name": "crypto_cipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
```

```json
{
  "name": "crypto_cipher_setkey",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586709856,
      "name": "crypto_cipher_setkey",
      "external": true,
      "loc": "crypto/cipher.c:43",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/skcipher.c:skcipher_setkey_simple",
        "crypto/ecb.c:lskcipher_setkey_simple2",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709856,
      "name": "crypto_cipher_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493886560,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495652156,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495704752,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495736448,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227367284,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3229006720,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 3229058728,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229085112,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287522000,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289786920,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289852980,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289888600,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273447578,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274805310,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274853034,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274886520,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582277482,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583808226,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583854227,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583881066,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582215242,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583745282,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791283,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583818122,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582267962,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791986,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837987,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583864826,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
  "name": "crypto_cipher_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582346522,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_set_derived_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583893074,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/skcipher.c:skcipher_setkey_simple"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939059,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583965898,
      "name": "crypto_cipher_setkey",
      "external": false,
      "loc": "include/linux/crypto.h:1744",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
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
int crypto_cipher_setkey(struct crypto_cipher * tfm, const u8 * key, unsigned int keylen)
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
