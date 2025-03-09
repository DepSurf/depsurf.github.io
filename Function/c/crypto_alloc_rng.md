# Function: <code>crypto_alloc_rng</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582694160,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:118",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582694160,
      "name": "crypto_alloc_rng",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582954702,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:118",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "security/keys/big_key.c:big_key_crypto_init",
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954336,
      "name": "crypto_alloc_rng",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583058974,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:118",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "security/keys/big_key.c:big_key_init",
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058608,
      "name": "crypto_alloc_rng",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583114110,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:114",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "security/keys/big_key.c:big_key_init",
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113744,
      "name": "crypto_alloc_rng",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288078,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:116",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287712,
      "name": "crypto_alloc_rng",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583496510,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:116",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583496144,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583617822,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:115",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617456,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583804562,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583804192,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583906402,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583906032,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584296866,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:114",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584295696,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584415506,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:114",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_instantiate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584414544,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584449858,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449696,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584847858,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847696,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585541485,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541312,
      "name": "crypto_alloc_rng",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586303821,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303616,
      "name": "crypto_alloc_rng",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586547613,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:133",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586547408,
      "name": "crypto_alloc_rng",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586817693,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:133",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817488,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495727764,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495727272,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229081296,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229080880,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289882336,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289881696,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274878830,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274878386,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583875138,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874768,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583812194,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583811824,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583858898,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583858528,
      "name": "crypto_alloc_rng",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct crypto_rng * crypto_alloc_rng(const char * alg_name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_alloc_rng",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959970,
      "name": "crypto_alloc_rng",
      "external": true,
      "loc": "crypto/rng.c:110",
      "file": "crypto/rng.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/rng.c:crypto_get_default_rng"
      ],
      "caller_func": [
        "crypto/drbg.c:drbg_kcapi_seed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959600,
      "name": "crypto_alloc_rng",
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
