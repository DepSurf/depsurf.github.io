# Function: <code>fscrypt_free_bounce_page</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215954,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214560,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582214608,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582296818,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295328,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582295376,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582581315,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580048,
      "name": "fscrypt_free_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582652547,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651280,
      "name": "fscrypt_free_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582681635,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680352,
      "name": "fscrypt_free_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583007101,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005792,
      "name": "fscrypt_free_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594018335,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583476000,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596057565,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069808,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584297990,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584295888,
      "name": "fscrypt_free_bounce_page",
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
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584514862,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:69",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512704,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493871836,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493869752,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446603336493869864,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227354408,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227352660,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3227352728,
      "name": "fscrypt_free_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287504480,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287502272,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055287502368,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273436580,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273435300,
      "name": "fscrypt_free_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265554,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264064,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582264112,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582203314,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201824,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582201872,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582256034,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254544,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582254592,
      "name": "fscrypt_free_bounce_page",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```

```json
{
  "name": "fscrypt_free_bounce_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582334626,
      "name": "fscrypt_free_bounce_page",
      "external": true,
      "loc": "fs/crypto/crypto.c:128",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333136,
      "name": "fscrypt_free_bounce_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582333184,
      "name": "fscrypt_free_bounce_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void fscrypt_free_bounce_page(struct page * bounce_page)
```
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
