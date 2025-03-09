# Function: <code>iomap_zero_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581360,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap.c:317",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_truncate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581360,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670320,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap.c:400",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670320,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724384,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap.c:396",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724384,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581870416,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap.c:396",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581870416,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053104,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap.c:403",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053104,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147168,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap.c:1032",
      "file": "fs/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147168,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298032,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298032,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582397008,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582397008,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582688854,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:984",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582686736,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582760582,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:953",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582757984,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582792566,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:953",
      "file": "fs/iomap/buffered-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786944,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583123216,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:930",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583123216,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:928",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594026153,
      "name": "iomap_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071583611392,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 851
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:1189",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596061994,
      "name": "iomap_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071584217696,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:1209",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596586134,
      "name": "iomap_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071584447248,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:1377",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597491936,
      "name": "iomap_zero_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071584670000,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493998376,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493998376,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227461920,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227461920,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287645264,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287645264,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273513198,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273513198,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582365744,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365744,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582303440,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582303440,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356224,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356224,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_zero_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435840,
      "name": "iomap_zero_range",
      "external": true,
      "loc": "fs/iomap/buffered-io.c:979",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_truncate_page",
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435840,
      "name": "iomap_zero_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int iomap_zero_range(struct inode * inode, loff_t pos, loff_t len, bool * did_zero, struct iomap_ops * ops)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops * ops</code> ➡️ <code>const struct iomap_ops * ops</code>
</li>
</ul>
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
