# Function: <code>crypto_cipher_encrypt_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586721029,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1557",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582943945,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1514",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582957924,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1514",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587169092,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1514",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583039339,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583044019,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047897,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583062436,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587368323,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581647679,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093371,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098210,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583103351,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117588,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587499959,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1517",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581793103,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1565",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259883,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1565",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583264802,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1565",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270020,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1565",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291578,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1565",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588022749,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1565",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581967409,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1578",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_do_page_crypto"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583467637,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1578",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583471954,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1578",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583477392,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1578",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500010,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1578",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588374012,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1578",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582053802,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1763",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583589605,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1763",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583594646,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1763",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583598320,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1763",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619194,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1763",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588564380,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1763",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582214858,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583778053,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583782254,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583785247,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805939,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582295618,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583879797,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583883480,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583888159,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583907459,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584215680,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:79",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:decrypt",
        "crypto/xts.c:encrypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584215680,
      "name": "crypto_cipher_encrypt_one",
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
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334048,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:79",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_decrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334048,
      "name": "crypto_cipher_encrypt_one",
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
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368592,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:80",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_decrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_ctr_crypt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368592,
      "name": "crypto_cipher_encrypt_one",
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
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763760,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:80",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_decrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763760,
      "name": "crypto_cipher_encrypt_one",
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
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585447152,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:80",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_decrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447152,
      "name": "crypto_cipher_encrypt_one",
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
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205392,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:80",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_decrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205392,
      "name": "crypto_cipher_encrypt_one",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586443680,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:80",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_decrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586443680,
      "name": "crypto_cipher_encrypt_one",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
```

```json
{
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586709536,
      "name": "crypto_cipher_encrypt_one",
      "external": true,
      "loc": "crypto/cipher.c:80",
      "file": "crypto/cipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/xts.c:xts_decrypt",
        "crypto/xts.c:xts_encrypt",
        "crypto/ctr.c:crypto_ctr_crypt",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df",
        "crypto/drbg.c:drbg_ctr_df"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709536,
      "name": "crypto_cipher_encrypt_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493870640,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495698188,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495702000,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495706820,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495729052,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227353020,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 3229052596,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/cbc.c:crypto_cbc_encrypt",
        "crypto/cbc.c:crypto_cbc_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229055744,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229060596,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229084496,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287502828,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289845240,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289850276,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289856708,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289887780,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273435488,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274848320,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274851354,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274854972,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274881962,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582264354,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848533,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583852216,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856895,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583876195,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582202114,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785589,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583789272,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583793951,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813251,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582254834,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832293,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583835976,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840655,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583859955,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "crypto_cipher_encrypt_one",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582333426,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_generate_iv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933365,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/cbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583937048,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/xts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/xts.c:init_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583941727,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/ctr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ctr.c:crypto_ctr_crypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583961027,
      "name": "crypto_cipher_encrypt_one",
      "external": false,
      "loc": "include/linux/crypto.h:1760",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
void crypto_cipher_encrypt_one(struct crypto_cipher * tfm, u8 * dst, const u8 * src)
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
