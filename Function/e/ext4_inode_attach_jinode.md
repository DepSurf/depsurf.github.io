# Function: <code>ext4_inode_attach_jinode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581560160,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:3727",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560160,
      "name": "ext4_inode_attach_jinode.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071581571936,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581771624,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4035",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581746048,
      "name": "ext4_inode_attach_jinode.part.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071581758016,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581860860,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4161",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833776,
      "name": "ext4_inode_attach_jinode.part.68",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071581846848,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582009389,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4283",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981008,
      "name": "ext4_inode_attach_jinode.part.70",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071581996496,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159421,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4332",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130480,
      "name": "ext4_inode_attach_jinode.part.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071582146416,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582348765,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4380",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327680,
      "name": "ext4_inode_attach_jinode.part.72",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582335776,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582447885,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4410",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420560,
      "name": "ext4_inode_attach_jinode.part.76",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582434704,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582617473,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4422",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582589536,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582604112,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582718465,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690288,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582704928,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583016128,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4105",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016128,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583091344,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4141",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091344,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583116304,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4140",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116304,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583457088,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4063",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457088,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980000,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4133",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980000,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584608528,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4219",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608528,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835008,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4004",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_open",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835008,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067872,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4023",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067872,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494375832,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494341680,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446603336494362752,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227812400,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227777036,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 3227796588,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288110568,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288070672,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 13835058055288094304,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273801870,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273777328,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446743936273790886,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582687201,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659024,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582673664,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582624369,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596192,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582610832,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582677057,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582648880,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582663520,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_inode_attach_jinode(struct inode * inode)
```

```json
{
  "name": "ext4_inode_attach_jinode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582761095,
      "name": "ext4_inode_attach_jinode",
      "external": true,
      "loc": "fs/ext4/inode.c:4408",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/verity.c:ext4_begin_enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730288,
      "name": "ext4_inode_attach_jinode.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071582747232,
      "name": "ext4_inode_attach_jinode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
