# Function: <code>fscrypt_get_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(struct inode * inode, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500592,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:92",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500592,
      "name": "fscrypt_get_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
struct fscrypt_ctx * fscrypt_get_ctx(const struct inode * inode, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581585888,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:91",
      "file": "fs/crypto/crypto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585888,
      "name": "fscrypt_get_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct fscrypt_ctx * fscrypt_get_ctx(const struct inode * inode, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647248,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:91",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647248,
      "name": "fscrypt_get_ctx.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071581647440,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(const struct inode * inode, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581793773,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:91",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792720,
      "name": "fscrypt_get_ctx.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071581792912,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(const struct inode * inode, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968056,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:98",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966736,
      "name": "fscrypt_get_ctx.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071581966928,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(const struct inode * inode, gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582054968,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:98",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053488,
      "name": "fscrypt_get_ctx.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071582053680,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582214384,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214384,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582295152,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295152,
      "name": "fscrypt_get_ctx",
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493869912,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493869912,
      "name": "fscrypt_get_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227352480,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227352480,
      "name": "fscrypt_get_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287501952,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287501952,
      "name": "fscrypt_get_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273434984,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273434984,
      "name": "fscrypt_get_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582263888,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263888,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582201648,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201648,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582254368,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254368,
      "name": "fscrypt_get_ctx",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
```

```json
{
  "name": "fscrypt_get_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332960,
      "name": "fscrypt_get_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:90",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332960,
      "name": "fscrypt_get_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(struct inode * inode, gfp_t gfp_flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct inode * inode</code> ➡️ <code>const struct inode * inode</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct inode * inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, gfp_flags</code> ➡️ <code>gfp_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct fscrypt_ctx * fscrypt_get_ctx(gfp_t gfp_flags)
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
