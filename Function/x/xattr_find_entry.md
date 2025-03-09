# Function: <code>xattr_find_entry</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566192,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566192,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667616,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667616,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582840192,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840192,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582944336,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582944336,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259296,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:283",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259296,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583360224,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:283",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360224,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583383536,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:283",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383536,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727760,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:283",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727760,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584283104,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:283",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283104,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931024,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:285",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931024,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585158592,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:323",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158592,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585391232,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:323",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_ibody_find",
        "fs/ext4/xattr.c:ext4_xattr_block_find",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585391232,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494619264,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494619264,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228063372,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228063372,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288424336,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288424336,
      "name": "xattr_find_entry",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273993724,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273993724,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582913072,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913072,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582850224,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582850224,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901680,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901680,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```

```json
{
  "name": "xattr_find_entry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582988752,
      "name": "xattr_find_entry",
      "external": false,
      "loc": "fs/ext4/xattr.c:281",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988752,
      "name": "xattr_find_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int xattr_find_entry(struct inode * inode, struct ext4_xattr_entry * * pentry, void * end, int name_index, const char * name, int sorted)
```
</details>
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
