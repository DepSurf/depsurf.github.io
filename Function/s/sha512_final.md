# Function: <code>sha512_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582681160,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:150",
      "file": "crypto/sha512_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682208,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932160,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:150",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932160,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583034592,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:150",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034592,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583088640,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:150",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583088640,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583255072,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:150",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583255072,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583462816,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:150",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583462816,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583584784,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:172",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583584784,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773728,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773728,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875472,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875472,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584265696,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584265696,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384432,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384432,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418944,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418944,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584816176,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:164",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816176,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585507168,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:164",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585507168,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586269904,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:164",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586269904,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586511504,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:164",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511504,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586780896,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:164",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780896,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495694092,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495694552,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229046548,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229046952,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289839216,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289839216,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274841862,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274842694,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844208,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844208,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781264,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781264,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827968,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827968,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int sha512_final(struct shash_desc * desc, u8 * hash)
```

```json
{
  "name": "sha512_final",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583929040,
      "name": "sha512_final",
      "external": false,
      "loc": "crypto/sha512_generic.c:167",
      "file": "crypto/sha512_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929040,
      "name": "sha512_final",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
