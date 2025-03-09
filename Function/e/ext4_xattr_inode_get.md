# Function: <code>ext4_xattr_inode_get</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231520,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:426",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231520,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380608,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:445",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380608,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571456,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571456,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582680336,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680336,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845424,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845424,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949568,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949568,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583263280,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:468",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583263280,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583364192,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:468",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364192,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387312,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:468",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387312,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731664,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:468",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731664,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584287184,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:483",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287184,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:499",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584935856,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071596085148,
      "name": "ext4_xattr_inode_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:528",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163408,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071596608628,
      "name": "ext4_xattr_inode_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:528",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get",
        "fs/ext4/xattr.c:ext4_xattr_block_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396176,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071597514283,
      "name": "ext4_xattr_inode_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494625248,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494625248,
      "name": "ext4_xattr_inode_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228070172,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228070172,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288431856,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288431856,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273995340,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273995340,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582918304,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918304,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582855456,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582855456,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906912,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906912,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```

```json
{
  "name": "ext4_xattr_inode_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582993984,
      "name": "ext4_xattr_inode_get",
      "external": false,
      "loc": "fs/ext4/xattr.c:466",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_move_to_block",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_xattr_ibody_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582993984,
      "name": "ext4_xattr_inode_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_xattr_inode_get(struct inode * inode, struct ext4_xattr_entry * entry, void * buffer, size_t size)
```
</details>
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
