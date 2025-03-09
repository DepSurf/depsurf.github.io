# Function: <code>ext4_fname_setup_ci_filename</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582697440,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697440,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582799632,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799632,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583112064,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1314",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112064,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583191088,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1303",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191088,
      "name": "ext4_fname_setup_ci_filename",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct ext4_filename * name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218864,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1372",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218864,
      "name": "ext4_fname_setup_ci_filename",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct ext4_filename * name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562576,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1373",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562576,
      "name": "ext4_fname_setup_ci_filename",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct ext4_filename * name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099296,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1419",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099296,
      "name": "ext4_fname_setup_ci_filename",
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
int ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct ext4_filename * name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584732912,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1424",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584732912,
      "name": "ext4_fname_setup_ci_filename",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct ext4_filename * name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584956224,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1441",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956224,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
int ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct ext4_filename * name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585187248,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1445",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/crypto.c:ext4_fname_prepare_lookup",
        "fs/ext4/crypto.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585187248,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494469704,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494469704,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227906148,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_add_entry",
        "fs/ext4/namei.c:ext4_find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227906148,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288227328,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288227328,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273875056,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273875056,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582768368,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768368,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582705536,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582705536,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```

```json
{
  "name": "ext4_fname_setup_ci_filename",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582843520,
      "name": "ext4_fname_setup_ci_filename",
      "external": true,
      "loc": "fs/ext4/namei.c:1310",
      "file": "fs/ext4/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/namei.c:ext4_fname_prepare_lookup",
        "fs/ext4/namei.c:ext4_fname_setup_filename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843520,
      "name": "ext4_fname_setup_ci_filename",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_filename * name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fscrypt_str * cf_name</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
void ext4_fname_setup_ci_filename(struct inode * dir, const struct qstr * iname, struct fscrypt_str * cf_name)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
