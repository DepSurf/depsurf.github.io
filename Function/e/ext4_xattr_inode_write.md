# Function: <code>ext4_xattr_inode_write</code>

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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582235106,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1300",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582383624,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1321",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582572565,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1349",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582672305,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1341",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582846470,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582950614,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262192,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1324",
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
      "addr": 18446744071583262192,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363088,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1327",
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
      "addr": 18446744071583363088,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583385808,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1327",
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
      "addr": 18446744071583385808,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
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
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1330",
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
      "addr": 18446744071583730144,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
    },
    {
      "addr": 18446744071592272032,
      "name": "ext4_xattr_inode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1339",
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
      "addr": 18446744071584284512,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
    },
    {
      "addr": 18446744071594053538,
      "name": "ext4_xattr_inode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1355",
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
      "addr": 18446744071584934240,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    },
    {
      "addr": 18446744071596084949,
      "name": "ext4_xattr_inode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1383",
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
      "addr": 18446744071585161776,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    },
    {
      "addr": 18446744071596608445,
      "name": "ext4_xattr_inode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1383",
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
      "addr": 18446744071585394544,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    },
    {
      "addr": 18446744071597514100,
      "name": "ext4_xattr_inode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494623332,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228065252,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
      "addr": 3228065252,
      "name": "ext4_xattr_inode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288433200,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273998440,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582919350,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582856502,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582907958,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
  "name": "ext4_xattr_inode_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582995030,
      "name": "ext4_xattr_inode_write",
      "external": false,
      "loc": "fs/ext4/xattr.c:1342",
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
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int ext4_xattr_inode_write(handle_t * handle, struct inode * ea_inode, const void * buf, int bufsize)
```
</details>
</li>
</ul>
