# Function: <code>generic_write_check_limits</code>

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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580927360,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2915",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580927360,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581023440,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2951",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023440,
      "name": "generic_write_check_limits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078736,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078736,
      "name": "generic_write_check_limits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581262176,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2914",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581262176,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123392,
      "name": "generic_write_check_limits",
      "external": true,
      "loc": "fs/read_write.c:1605",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_write_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123392,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148272,
      "name": "generic_write_check_limits",
      "external": true,
      "loc": "fs/read_write.c:1610",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_write_checks",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148272,
      "name": "generic_write_check_limits",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465104,
      "name": "generic_write_check_limits",
      "external": true,
      "loc": "fs/read_write.c:1601",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_write_checks",
        "fs/read_write.c:vfs_copy_file_range",
        "fs/remap_range.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465104,
      "name": "generic_write_check_limits",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984768,
      "name": "generic_write_check_limits",
      "external": true,
      "loc": "fs/read_write.c:1626",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_write_checks",
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984768,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583544976,
      "name": "generic_write_check_limits",
      "external": true,
      "loc": "fs/read_write.c:1630",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_write_checks",
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583544976,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760928,
      "name": "generic_write_check_limits",
      "external": true,
      "loc": "fs/read_write.c:1629",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_write_checks",
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760928,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963616,
      "name": "generic_write_check_limits",
      "external": true,
      "loc": "fs/read_write.c:1646",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_write_checks",
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963616,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492441656,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492441656,
      "name": "generic_write_check_limits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226317936,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226317936,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285716112,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285716112,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272518392,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272518392,
      "name": "generic_write_check_limits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581047584,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047584,
      "name": "generic_write_check_limits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580994864,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994864,
      "name": "generic_write_check_limits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581038784,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038784,
      "name": "generic_write_check_limits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_write_check_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581100416,
      "name": "generic_write_check_limits",
      "external": false,
      "loc": "mm/filemap.c:2905",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_write_iter",
        "mm/filemap.c:generic_copy_file_checks",
        "mm/filemap.c:generic_remap_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100416,
      "name": "generic_write_check_limits.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
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
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int generic_write_check_limits(struct file * file, loff_t pos, loff_t * count)
```
</details>
</li>
</ul>
