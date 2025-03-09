# Function: <code>utf8_casefold</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583059712,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583059712,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166128,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166128,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488704,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488704,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583596992,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:105",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583596992,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620000,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:105",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/hash.c:ext4fs_dirhash",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620000,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583979024,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:105",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/hash.c:ext4fs_dirhash",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979024,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584560576,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:99",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/hash.c:ext4fs_dirhash",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560576,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585237920,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:99",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/hash.c:ext4fs_dirhash",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237920,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585467488,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:99",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/hash.c:ext4fs_dirhash",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585467488,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585702464,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:99",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/hash.c:ext4fs_dirhash",
        "fs/ext4/namei.c:ext4_fname_setup_ci_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702464,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494878952,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494878952,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228294540,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228294540,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288738720,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288738720,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274196386,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274196386,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583134864,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134864,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072016,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072016,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```

```json
{
  "name": "utf8_casefold",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583212656,
      "name": "utf8_casefold",
      "external": true,
      "loc": "fs/unicode/utf8-core.c:104",
      "file": "fs/unicode/utf8-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/ext4/hash.c:ext4fs_dirhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583212656,
      "name": "utf8_casefold",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int utf8_casefold(const struct unicode_map * um, const struct qstr * str, unsigned char * dest, size_t dlen)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
