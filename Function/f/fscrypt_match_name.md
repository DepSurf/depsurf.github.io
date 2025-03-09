# Function: <code>fscrypt_match_name</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582093900,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt_supp.h:120",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582243212,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt_supp.h:122",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582432966,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt_supp.h:158",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582532518,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt_supp.h:158",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582702808,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:215",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582805016,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582272,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:517",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582272,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653056,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:486",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653056,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682144,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:482",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682144,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583007632,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:506",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583007632,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477728,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:512",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477728,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072064,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:536",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072064,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298736,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:536",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298736,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584515712,
      "name": "fscrypt_match_name",
      "external": true,
      "loc": "fs/crypto/fname.c:536",
      "file": "fs/crypto/fname.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584515712,
      "name": "fscrypt_match_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494475032,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227911460,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288234756,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273879314,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582773752,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582710920,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582762621,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
  "name": "fscrypt_match_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582848904,
      "name": "fscrypt_match_name",
      "external": false,
      "loc": "include/linux/fscrypt.h:226",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_find_dest_de",
        "fs/ext4/namei.c:ext4_search_dir"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name * fname, const u8 * de_name, u32 de_name_len)
```
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
