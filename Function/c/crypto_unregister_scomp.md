# Function: <code>crypto_unregister_scomp</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017472,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:342",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017472,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068944,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:341",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps",
        "crypto/lzo.c:lzo_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068944,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583234852,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:339",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234528,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583443220,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:292",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442896,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583565202,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:289",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564880,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583754626,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754320,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583864338,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864032,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584254226,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254160,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584372962,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372896,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584407394,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407328,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584802770,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802704,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585492354,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492288,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586254450,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586254368,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586494818,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:268",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494736,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586764866,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:274",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/deflate.c:deflate_mod_fini",
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764784,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495681712,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495681368,
      "name": "crypto_unregister_scomp",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229032884,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229032636,
      "name": "crypto_unregister_scomp",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289825600,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289825136,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274830812,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274830554,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583833074,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832768,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583770130,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769824,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583816834,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583816528,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int crypto_unregister_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_unregister_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583917906,
      "name": "crypto_unregister_scomp",
      "external": true,
      "loc": "crypto/scompress.c:269",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_unregister_scomps",
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_fini",
        "crypto/lzo-rle.c:lzorle_mod_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917600,
      "name": "crypto_unregister_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int crypto_unregister_scomp(struct scomp_alg * alg)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
