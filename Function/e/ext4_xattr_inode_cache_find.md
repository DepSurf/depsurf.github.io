# Function: <code>ext4_xattr_inode_cache_find</code>

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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582234590,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1416",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582383082,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1437",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582572112,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1465",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582671825,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1463",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582846048,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582950192,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265712,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1448",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265712,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583366832,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1450",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583366832,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389344,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1450",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389344,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733440,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1454",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733440,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291296,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1463",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291296,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584939872,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1489",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584939872,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167248,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1517",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167248,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
```

```json
{
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585400016,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1517",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585400016,
      "name": "ext4_xattr_inode_cache_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494622936,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228070896,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288432652,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273998078,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582918928,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582856080,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582907536,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
  "name": "ext4_xattr_inode_cache_find",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582994608,
      "name": "ext4_xattr_inode_cache_find",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
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
struct inode * ext4_xattr_inode_cache_find(struct inode * inode, const void * value, size_t value_len, u32 hash)
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
