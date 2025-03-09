# Function: <code>generic_copy_file_checks</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581048192,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3119",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048192,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103856,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103856,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286288,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3085",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286288,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123856,
      "name": "generic_copy_file_checks",
      "external": false,
      "loc": "fs/read_write.c:1422",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123856,
      "name": "generic_copy_file_checks.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582148834,
      "name": "generic_copy_file_checks",
      "external": false,
      "loc": "fs/read_write.c:1427",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582465666,
      "name": "generic_copy_file_checks",
      "external": false,
      "loc": "fs/read_write.c:1418",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582985566,
      "name": "generic_copy_file_checks",
      "external": false,
      "loc": "fs/read_write.c:1410",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583545875,
      "name": "generic_copy_file_checks",
      "external": false,
      "loc": "fs/read_write.c:1405",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583761814,
      "name": "generic_copy_file_checks",
      "external": false,
      "loc": "fs/read_write.c:1404",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583964533,
      "name": "generic_copy_file_checks",
      "external": false,
      "loc": "fs/read_write.c:1412",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_copy_file_range"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492467512,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492467512,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226345288,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226345288,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285751600,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285751600,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272538934,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272538934,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072704,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072704,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019888,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019888,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063904,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063904,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```

```json
{
  "name": "generic_copy_file_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125456,
      "name": "generic_copy_file_checks",
      "external": true,
      "loc": "mm/filemap.c:3076",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_copy_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125456,
      "name": "generic_copy_file_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int generic_copy_file_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, size_t * req_count, unsigned int flags)
```
</details>
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
