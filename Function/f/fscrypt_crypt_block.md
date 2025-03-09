# Function: <code>fscrypt_crypt_block</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216568,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582215104,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582297416,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582295952,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:93",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582581944,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582580464,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:93",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591341417,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582651696,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:93",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591284150,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582680768,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:93",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592239518,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583006208,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:101",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594017810,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071583476512,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070720,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:101",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070720,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296816,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:101",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296816,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493870976,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493870976,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227353360,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227353360,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287503376,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287503376,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273435844,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273435844,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266152,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582264688,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203912,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582202448,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582256632,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582255168,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_crypt_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fscrypt_crypt_block",
      "external": true,
      "loc": "fs/crypto/crypto.c:152",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_decrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks",
        "fs/crypto/crypto.c:fscrypt_encrypt_block_inplace",
        "fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks",
        "fs/crypto/bio.c:fscrypt_zeroout_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335224,
      "name": "fscrypt_crypt_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582333760,
      "name": "fscrypt_crypt_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int fscrypt_crypt_block(const struct inode * inode, fscrypt_direction_t rw, u64 lblk_num, struct page * src_page, struct page * dest_page, unsigned int len, unsigned int offs, gfp_t gfp_flags)
```
</details>
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
