# Function: <code>generic_remap_checks</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952768,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2972",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952768,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047680,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:3018",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047680,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103344,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103344,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581285776,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2984",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285776,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
  "name": "generic_remap_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582409696,
      "name": "generic_remap_checks",
      "external": false,
      "loc": "fs/remap_range.c:29",
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
      "addr": 18446744071582409696,
      "name": "generic_remap_checks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
  "name": "generic_remap_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582439019,
      "name": "generic_remap_checks",
      "external": false,
      "loc": "fs/remap_range.c:29",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:generic_remap_file_range_prep"
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
  "name": "generic_remap_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582761803,
      "name": "generic_remap_checks",
      "external": false,
      "loc": "fs/remap_range.c:29",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:generic_remap_file_range_prep"
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
  "name": "generic_remap_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583307536,
      "name": "generic_remap_checks",
      "external": false,
      "loc": "fs/remap_range.c:29",
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
      "addr": 18446744071583307536,
      "name": "generic_remap_checks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
  "name": "generic_remap_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583893184,
      "name": "generic_remap_checks",
      "external": false,
      "loc": "fs/remap_range.c:30",
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
      "addr": 18446744071583893184,
      "name": "generic_remap_checks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
  "name": "generic_remap_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584116160,
      "name": "generic_remap_checks",
      "external": false,
      "loc": "fs/remap_range.c:31",
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
      "addr": 18446744071584116160,
      "name": "generic_remap_checks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
  "name": "generic_remap_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584332704,
      "name": "generic_remap_checks",
      "external": false,
      "loc": "fs/remap_range.c:31",
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
      "addr": 18446744071584332704,
      "name": "generic_remap_checks.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492466944,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492466944,
      "name": "generic_remap_checks",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226344168,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226344168,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285750864,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285750864,
      "name": "generic_remap_checks",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272538514,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272538514,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072192,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072192,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019376,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019376,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063392,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063392,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
```

```json
{
  "name": "generic_remap_checks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124944,
      "name": "generic_remap_checks",
      "external": true,
      "loc": "mm/filemap.c:2975",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:generic_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124944,
      "name": "generic_remap_checks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int generic_remap_checks(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * req_count, unsigned int remap_flags)
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
