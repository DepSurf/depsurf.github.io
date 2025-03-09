# Function: <code>fscrypt_release_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581501280,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:63",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_restore_control_page",
        "fs/crypto/crypto.c:completion_pages",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501280,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581586528,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_restore_control_page",
        "fs/crypto/crypto.c:completion_pages",
        "fs/crypto/crypto.c:fscrypt_zeroout_range",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586528,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581647056,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_restore_control_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647056,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581792528,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:62",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_restore_control_page",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792528,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581966544,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:69",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_restore_control_page",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966544,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582053296,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:69",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/crypto.c:fscrypt_restore_control_page",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/crypto/bio.c:fscrypt_zeroout_range",
        "fs/crypto/bio.c:completion_pages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053296,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582214272,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:mpage_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214272,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582295040,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295040,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493870248,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493870248,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227352368,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227352368,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287501760,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287501760,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273434864,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273434864,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582263776,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263776,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582201536,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201536,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582254256,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254256,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```

```json
{
  "name": "fscrypt_release_ctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332848,
      "name": "fscrypt_release_ctx",
      "external": true,
      "loc": "fs/crypto/crypto.c:68",
      "file": "fs/crypto/crypto.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/crypto/bio.c:completion_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332848,
      "name": "fscrypt_release_ctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void fscrypt_release_ctx(struct fscrypt_ctx * ctx)
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
