# Function: <code>vfs_dedupe_file_range_compare</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int vfs_dedupe_file_range_compare(struct inode * src, loff_t srcoff, struct inode * dest, loff_t destoff, loff_t len, bool * is_same)
```

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222416,
      "name": "vfs_dedupe_file_range_compare",
      "external": true,
      "loc": "fs/read_write.c:1878",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222416,
      "name": "vfs_dedupe_file_range_compare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 771
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
int vfs_dedupe_file_range_compare(struct inode * src, loff_t srcoff, struct inode * dest, loff_t destoff, loff_t len, bool * is_same)
```

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270112,
      "name": "vfs_dedupe_file_range_compare",
      "external": true,
      "loc": "fs/read_write.c:1894",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270112,
      "name": "vfs_dedupe_file_range_compare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
int vfs_dedupe_file_range_compare(struct inode * src, loff_t srcoff, struct inode * dest, loff_t destoff, loff_t len, bool * is_same)
```

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409152,
      "name": "vfs_dedupe_file_range_compare",
      "external": true,
      "loc": "fs/read_write.c:1897",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409152,
      "name": "vfs_dedupe_file_range_compare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 700
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
int vfs_dedupe_file_range_compare(struct inode * src, loff_t srcoff, struct inode * dest, loff_t destoff, loff_t len, bool * is_same)
```

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581566055,
      "name": "vfs_dedupe_file_range_compare",
      "external": true,
      "loc": "fs/read_write.c:1924",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_clone_file_prep_inodes"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_clone_file_prep_inodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564768,
      "name": "vfs_dedupe_file_range_compare.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
    },
    {
      "addr": 18446744071581565536,
      "name": "vfs_dedupe_file_range_compare",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581651298,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1800",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581768468,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1882",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581840869,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582061952,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1964",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061952,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582411008,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/remap_range.c:202",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411008,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582437808,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/remap_range.c:202",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582437808,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582760592,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/remap_range.c:190",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760592,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/remap_range.c:191",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309120,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
    },
    {
      "addr": 18446744071594011679,
      "name": "vfs_dedupe_file_range_compare.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/remap_range.c:183",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:__generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893664,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
    },
    {
      "addr": 18446744071596051921,
      "name": "vfs_dedupe_file_range_compare.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/remap_range.c:186",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:__generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116640,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
    },
    {
      "addr": 18446744071596574453,
      "name": "vfs_dedupe_file_range_compare.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/remap_range.c:192",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:__generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334528,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
    },
    {
      "addr": 18446744071597479136,
      "name": "vfs_dedupe_file_range_compare.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493302968,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493302968,
      "name": "vfs_dedupe_file_range_compare.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226907684,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286845552,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273046334,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581809605,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581747269,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581800917,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
  "name": "vfs_dedupe_file_range_compare",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581870077,
      "name": "vfs_dedupe_file_range_compare",
      "external": false,
      "loc": "fs/read_write.c:1880",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int vfs_dedupe_file_range_compare(struct inode * src, loff_t srcoff, struct inode * dest, loff_t destoff, loff_t len, bool * is_same)
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int vfs_dedupe_file_range_compare(struct inode * src, loff_t srcoff, struct inode * dest, loff_t destoff, loff_t len, bool * is_same)
```
</details>
</li>
</ul>
