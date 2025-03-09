# Function: <code>alloc_empty_file</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581666243,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:133",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581667135,
      "name": "alloc_empty_file.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581666080,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581784277,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784277,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581783216,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581856501,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856501,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581855440,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582081365,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582079568,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:133",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339258,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582125952,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:133",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281972,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071582151536,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:133",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592228908,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071582467648,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:170",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008448,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071582988880,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583549552,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:170",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549552,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583765680,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:188",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583765680,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968384,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:185",
      "file": "fs/file_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_create",
        "fs/open.c:dentry_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968384,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493323032,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493323032,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226919996,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226919996,
      "name": "alloc_empty_file",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286863600,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:dentry_open",
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286863600,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273056632,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273056632,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581825237,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825237,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581824176,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581762901,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762901,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581761840,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581816549,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816549,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581815488,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
```

```json
{
  "name": "alloc_empty_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581885749,
      "name": "alloc_empty_file",
      "external": true,
      "loc": "fs/file_table.c:134",
      "file": "fs/file_table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/file_table.c:alloc_file",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885749,
      "name": "alloc_empty_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581884688,
      "name": "alloc_empty_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct file * alloc_empty_file(int flags, const struct cred * cred)
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
