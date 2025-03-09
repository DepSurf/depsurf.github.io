# Function: <code>do_splice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581202941,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1350",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_splice"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581367616,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1354",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_splice"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581445296,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1117",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_splice"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581499637,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1113",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_splice"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581641765,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1097",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_splice"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581796496,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1098",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581796496,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1413
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883056,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1102",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883056,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1440
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582008848,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1099",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008848,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1593
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086800,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086800,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582327664,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1093",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327664,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 966
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378704,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1010",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_splice",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378704,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405760,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1028",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_splice",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405760,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727536,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1030",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_splice",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727536,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 827
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583273088,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1026",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_splice",
        "io_uring/io_uring.c:io_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273088,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855472,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1025",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_splice",
        "io_uring/splice.c:io_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855472,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076112,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1246",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "io_uring/splice.c:io_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076112,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1331
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
ssize_t do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292224,
      "name": "do_splice",
      "external": true,
      "loc": "fs/splice.c:1305",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "fs/splice.c:__do_splice",
        "io_uring/splice.c:io_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292224,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1283
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493624704,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__arm64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493624704,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1420
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227164600,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227164600,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1708
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287211616,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287211616,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1916
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273264468,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273264468,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055536,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055536,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993088,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993088,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582046816,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582046816,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_splice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118496,
      "name": "do_splice",
      "external": false,
      "loc": "fs/splice.c:1100",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_splice",
        "fs/splice.c:__x64_sys_splice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118496,
      "name": "do_splice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1609
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
long int do_splice(struct file * in, loff_t * off_in, struct file * out, loff_t * off_out, size_t len, unsigned int flags)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
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
