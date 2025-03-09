# Function: <code>crypto_larval_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg * crypto_larval_lookup(const char * name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582632048,
      "name": "crypto_larval_lookup",
      "external": true,
      "loc": "crypto/api.c:207",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_alg_mod_lookup",
        "crypto/ablkcipher.c:crypto_givcipher_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632048,
      "name": "crypto_larval_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct crypto_alg * crypto_larval_lookup(const char * name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582881616,
      "name": "crypto_larval_lookup",
      "external": true,
      "loc": "crypto/api.c:207",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_alg_mod_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881616,
      "name": "crypto_larval_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct crypto_alg * crypto_larval_lookup(const char * name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978176,
      "name": "crypto_larval_lookup",
      "external": true,
      "loc": "crypto/api.c:207",
      "file": "crypto/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/api.c:crypto_alg_mod_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978176,
      "name": "crypto_larval_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct crypto_alg * crypto_larval_lookup(const char * name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583028372,
      "name": "crypto_larval_lookup",
      "external": true,
      "loc": "crypto/api.c:207",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
      ],
      "caller_func": [
        "crypto/api.c:crypto_alg_mod_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583027984,
      "name": "crypto_larval_lookup.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071583028304,
      "name": "crypto_larval_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct crypto_alg * crypto_larval_lookup(const char * name, u32 type, u32 mask)
```

```json
{
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583193620,
      "name": "crypto_larval_lookup",
      "external": true,
      "loc": "crypto/api.c:208",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
      ],
      "caller_func": [
        "crypto/api.c:crypto_alg_mod_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583193232,
      "name": "crypto_larval_lookup.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071583193552,
      "name": "crypto_larval_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583401722,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:220",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583521594,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:220",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583709738,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:215",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583819354,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584214154,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584332506,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584367050,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584762218,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585445798,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:272",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586203718,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:271",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586442086,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:271",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586707942,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:271",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495625784,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228984120,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289750156,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274783804,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583788090,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583725146,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583771850,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
  "name": "crypto_larval_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583872842,
      "name": "crypto_larval_lookup",
      "external": false,
      "loc": "crypto/api.c:217",
      "file": "crypto/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alg_mod_lookup"
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct crypto_alg * crypto_larval_lookup(const char * name, u32 type, u32 mask)
```
</details>
</li>
</ul>
