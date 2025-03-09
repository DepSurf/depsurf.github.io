# Function: <code>ext4_issue_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581752304,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:389",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752304,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581840416,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:396",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_zeroout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840416,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581990096,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:402",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990096,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582139632,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:412",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139632,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582328608,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:413",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328608,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582427200,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:413",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582427200,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582596432,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:417",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596432,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582697184,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697184,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009200,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:407",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009200,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583084672,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:418",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583084672,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583109696,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:419",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109696,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:418",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592258347,
      "name": "ext4_issue_zeroout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071583449200,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:417",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594039596,
      "name": "ext4_issue_zeroout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583970736,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:423",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596072598,
      "name": "ext4_issue_zeroout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071584598688,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:395",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596596101,
      "name": "ext4_issue_zeroout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071584824992,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:395",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597501620,
      "name": "ext4_issue_zeroout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585057952,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494354040,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494354040,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227787100,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227787100,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288083120,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288083120,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273783752,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273783752,
      "name": "ext4_issue_zeroout",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582665920,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665920,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582603088,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603088,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582655776,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655776,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582739456,
      "name": "ext4_issue_zeroout",
      "external": true,
      "loc": "fs/ext4/inode.c:426",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "fs/ext4/inode.c:ext4_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582739456,
      "name": "ext4_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int ext4_issue_zeroout(struct inode * inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len)
```
</details>
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
