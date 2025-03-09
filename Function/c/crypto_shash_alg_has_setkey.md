# Function: <code>crypto_shash_alg_has_setkey</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583218630,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/hmac.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583426774,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429955,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583447080,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/hmac.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583547974,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583551347,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583569064,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:88",
      "file": "crypto/hmac.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583737142,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583740515,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757969,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583846902,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850275,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583867697,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584235814,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:94",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584240949,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:94",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256803,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:94",
      "file": "crypto/hmac.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584354598,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584359525,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584375607,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/hmac.c:hmac_create"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool crypto_shash_alg_has_setkey(struct shash_alg * alg)
```

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584393989,
      "name": "crypto_shash_alg_has_setkey",
      "external": true,
      "loc": "crypto/shash.c:36",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey",
        "crypto/hmac.c:hmac_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584391984,
      "name": "crypto_shash_alg_has_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool crypto_shash_alg_has_setkey(struct shash_alg * alg)
```

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584789221,
      "name": "crypto_shash_alg_has_setkey",
      "external": true,
      "loc": "crypto/shash.c:36",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey",
        "crypto/hmac.c:hmac_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787216,
      "name": "crypto_shash_alg_has_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool crypto_shash_alg_has_setkey(struct shash_alg * alg)
```

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585475297,
      "name": "crypto_shash_alg_has_setkey",
      "external": true,
      "loc": "crypto/shash.c:36",
      "file": "crypto/shash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": [
        "crypto/hmac.c:hmac_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585472960,
      "name": "crypto_shash_alg_has_setkey",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586229670,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586236193,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586258098,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/hmac.c:hmac_create"
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586466964,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_clone_ahash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586472201,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_clone_shash",
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:shash_async_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586498677,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:81",
      "file": "crypto/hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/hmac.c:hmac_create"
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586739485,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:79",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_clone_ahash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586744137,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:79",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_clone_shash",
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769220,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:79",
      "file": "crypto/hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/hmac.c:hmac_create"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495660448,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495664928,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495685720,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229014484,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 3229018188,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 3229035848,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289797684,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289803396,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289830164,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274812404,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583815638,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583819011,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836433,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583752694,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583756067,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583773489,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583799398,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802771,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583820193,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
  "name": "crypto_shash_alg_has_setkey",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583900678,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_alg_has_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583903811,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:crypto_shash_init_tfm",
        "crypto/shash.c:crypto_init_shash_ops_async",
        "crypto/shash.c:crypto_shash_setkey"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583921265,
      "name": "crypto_shash_alg_has_setkey",
      "external": false,
      "loc": "include/crypto/internal/hash.h:83",
      "file": "crypto/hmac.c",
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool crypto_shash_alg_has_setkey(struct shash_alg * alg)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool crypto_shash_alg_has_setkey(struct shash_alg * alg)
```
</details>
</li>
</ul>
