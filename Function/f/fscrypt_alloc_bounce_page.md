# Function: <code>fscrypt_alloc_bounce_page</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * fscrypt_alloc_bounce_page(struct fscrypt_ctx * ctx, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648380,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:208",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648592,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct page * fscrypt_alloc_bounce_page(struct fscrypt_ctx * ctx, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581793820,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:188",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794032,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct page * fscrypt_alloc_bounce_page(struct fscrypt_ctx * ctx, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968088,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:192",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966976,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct page * fscrypt_alloc_bounce_page(struct fscrypt_ctx * ctx, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055000,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:194",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053840,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215861,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214752,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582296725,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295520,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582581221,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580096,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582652453,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651328,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582681541,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680400,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583007007,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005840,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594018198,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583476064,
      "name": "fscrypt_alloc_bounce_page",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596057428,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069888,
      "name": "fscrypt_alloc_bounce_page",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584297889,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584295968,
      "name": "fscrypt_alloc_bounce_page",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584514710,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:50",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512784,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493871736,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493870488,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227354272,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227352872,
      "name": "fscrypt_alloc_bounce_page",
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287504368,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287502640,
      "name": "fscrypt_alloc_bounce_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273436506,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273435364,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265461,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264256,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582203221,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582202016,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582255941,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254736,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct page * fscrypt_alloc_bounce_page(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_alloc_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582334533,
      "name": "fscrypt_alloc_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:117",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333328,
      "name": "fscrypt_alloc_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct page * fscrypt_alloc_bounce_page(struct fscrypt_ctx * ctx, gfp_t gfp_flags)
```
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fscrypt_ctx * ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, gfp_flags</code> ➡️ <code>gfp_flags</code>
</li>
</ul>
</details>
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
