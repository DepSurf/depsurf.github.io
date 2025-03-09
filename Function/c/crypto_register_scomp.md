# Function: <code>crypto_register_scomp</code>

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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017296,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:315",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017296,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583068784,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:314",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_register_scomps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068784,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583234628,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:327",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234480,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583442996,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:280",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442848,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583564980,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:277",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564832,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583754413,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754272,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583864125,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863984,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584254313,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254112,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584373049,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372848,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584407481,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407280,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584802857,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802656,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585492473,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585492224,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586255257,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586254288,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586495625,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:255",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494656,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586765673,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:261",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/deflate.c:deflate_mod_init",
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764704,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495681500,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495681288,
      "name": "crypto_register_scomp",
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229032732,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229032572,
      "name": "crypto_register_scomp",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289825304,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289825040,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274830662,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274830488,
      "name": "crypto_register_scomp",
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583832861,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832720,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583769917,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769776,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583816621,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583816480,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
```

```json
{
  "name": "crypto_register_scomp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583917693,
      "name": "crypto_register_scomp",
      "external": true,
      "loc": "crypto/scompress.c:257",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_register_scomps"
      ],
      "caller_func": [
        "crypto/lzo.c:lzo_mod_init",
        "crypto/lzo-rle.c:lzorle_mod_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917552,
      "name": "crypto_register_scomp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int crypto_register_scomp(struct scomp_alg * alg)
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
