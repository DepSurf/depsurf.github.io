# Function: <code>ext4_xattr_inode_lookup_create</code>

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
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582234501,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1464",
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
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582382979,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1485",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571952,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571952,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1607
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671664,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1512",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671664,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1680
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845904,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845904,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1645
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950048,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950048,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266176,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1497",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266176,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367344,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1502",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367344,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389856,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1502",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389856,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733952,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1506",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733952,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 638
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291840,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1515",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291840,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584940448,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1541",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584940448,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585167808,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1568",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585167808,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585400576,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1568",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585400576,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494622808,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494622808,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1588
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228070792,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228070792,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288432464,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288432464,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2224
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273997968,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273997968,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1338
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582918784,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918784,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582855936,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582855936,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907392,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907392,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
```

```json
{
  "name": "ext4_xattr_inode_lookup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994464,
      "name": "ext4_xattr_inode_lookup_create",
      "external": false,
      "loc": "fs/ext4/xattr.c:1513",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994464,
      "name": "ext4_xattr_inode_lookup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
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
int ext4_xattr_inode_lookup_create(handle_t * handle, struct inode * inode, const void * value, size_t value_len, struct inode * * ret_inode)
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
