# Function: <code>ext4_ext_split</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749578,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1024",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581944217,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1030",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582034249,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1030",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581896657,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1030",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582046833,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1030",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228992,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1024",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228992,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2344
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324112,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1024",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324112,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2344
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494256,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494256,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2473
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593792,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593792,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2473
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906000,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1005",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906000,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2068
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582977872,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1003",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977872,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2068
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583003600,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1004",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003600,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2076
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583338144,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1042",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338144,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2027
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583845968,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1044",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845968,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2055
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469920,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1052",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469920,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2077
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698800,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1052",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698800,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2094
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931408,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1052",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931408,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2109
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494243888,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494243888,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2424
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227675220,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227675220,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2676
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287946592,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287946592,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2920
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273695120,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273695120,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2192
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562528,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562528,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2473
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499696,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499696,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2473
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552640,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552640,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2473
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
```

```json
{
  "name": "ext4_ext_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582633824,
      "name": "ext4_ext_split",
      "external": false,
      "loc": "fs/ext4/extents.c:1028",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_create_new_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582633824,
      "name": "ext4_ext_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2459
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
int ext4_ext_split(handle_t * handle, struct inode * inode, unsigned int flags, struct ext4_ext_path * path, struct ext4_extent * newext, int at)
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
