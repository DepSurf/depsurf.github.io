# Function: <code>remap_verify_area</code>

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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648000,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1715",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648000,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764576,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764576,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581836784,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836784,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059248,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1862",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059248,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408688,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/remap_range.c:99",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408688,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582436453,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/remap_range.c:99",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
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
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582759205,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/remap_range.c:99",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
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
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583308665,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/remap_range.c:100",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
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
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583895129,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/remap_range.c:101",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
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
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584119183,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/remap_range.c:102",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:do_clone_file_range",
        "fs/remap_range.c:do_clone_file_range"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584333184,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/remap_range.c:102",
      "file": "fs/remap_range.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:vfs_dedupe_file_range",
        "fs/remap_range.c:vfs_clone_file_range",
        "fs/remap_range.c:vfs_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333184,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493300728,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493300728,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226903080,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range",
        "fs/read_write.c:do_clone_file_range",
        "fs/read_write.c:do_clone_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226903080,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286840048,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286840048,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273044908,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273044908,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805520,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805520,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581743184,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743184,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796832,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796832,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```

```json
{
  "name": "remap_verify_area",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866000,
      "name": "remap_verify_area",
      "external": false,
      "loc": "fs/read_write.c:1778",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866000,
      "name": "remap_verify_area",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int remap_verify_area(struct file * file, loff_t pos, loff_t len, bool write)
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
