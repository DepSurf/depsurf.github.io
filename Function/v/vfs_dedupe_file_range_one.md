# Function: <code>vfs_dedupe_file_range_one</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648160,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2053",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648160,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581764736,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2126",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764736,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581836944,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836944,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582060154,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2208",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059408,
      "name": "vfs_dedupe_file_range_one.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071582059696,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582408848,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/remap_range.c:446",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408848,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582435888,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/remap_range.c:449",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435888,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582758640,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/remap_range.c:437",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758640,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583308000,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/remap_range.c:427",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308000,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583894416,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/remap_range.c:436",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894416,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584118480,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/remap_range.c:439",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118480,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584333456,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/remap_range.c:432",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333456,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493300936,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493300936,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226903292,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226903292,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286840320,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286840320,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273045082,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273045082,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581805680,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805680,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581743344,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743344,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796992,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796992,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```

```json
{
  "name": "vfs_dedupe_file_range_one",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581866160,
      "name": "vfs_dedupe_file_range_one",
      "external": true,
      "loc": "fs/read_write.c:2124",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866160,
      "name": "vfs_dedupe_file_range_one",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
loff_t vfs_dedupe_file_range_one(struct file * src_file, loff_t src_pos, struct file * dst_file, loff_t dst_pos, loff_t len, unsigned int remap_flags)
```
</details>
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
