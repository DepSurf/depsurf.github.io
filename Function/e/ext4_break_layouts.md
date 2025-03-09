# Function: <code>ext4_break_layouts</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582335504,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4207",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582335504,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582434432,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4239",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434432,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582603872,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4251",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603872,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582704688,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704688,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015888,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:3926",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015888,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091104,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:3961",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091104,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583116064,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:3960",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116064,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583456832,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:3884",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456832,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583979696,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:3949",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979696,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584608208,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4035",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608208,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584834688,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:3824",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584834688,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585067552,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:3841",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067552,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494362472,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494362472,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227796484,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227796484,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288093936,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288093936,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273790672,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273790672,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582673424,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582673424,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582610592,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610592,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582663280,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663280,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ext4_break_layouts(struct inode * inode)
```

```json
{
  "name": "ext4_break_layouts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582746992,
      "name": "ext4_break_layouts",
      "external": true,
      "loc": "fs/ext4/inode.c:4228",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_punch_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582746992,
      "name": "ext4_break_layouts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int ext4_break_layouts(struct inode * inode)
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
