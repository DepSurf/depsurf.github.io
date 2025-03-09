# Function: <code>io_uring_setup</code>

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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582193056,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3406",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582193056,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274016,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274016,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582538592,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:8276",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582538592,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608944,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:9834",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608944,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582621856,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:9756",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582621856,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945712,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:10429",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945712,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_uring_setup",
      "external": false,
      "loc": "io_uring/io_uring.c:12118",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_setup",
        "io_uring/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015200,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071594125483,
      "name": "io_uring_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586762672,
      "name": "io_uring_setup",
      "external": false,
      "loc": "io_uring/io_uring.c:3713",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_setup",
        "io_uring/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762672,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587029232,
      "name": "io_uring_setup",
      "external": false,
      "loc": "io_uring/io_uring.c:4024",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_setup",
        "io_uring/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029232,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587327088,
      "name": "io_uring_setup",
      "external": false,
      "loc": "io_uring/io_uring.c:4033",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_setup",
        "io_uring/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587327088,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493842152,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__arm64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493842152,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227347596,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227347596,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287472000,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287472000,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273419338,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__se_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273419338,
      "name": "io_uring_setup",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582242752,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582242752,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180480,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180480,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233232,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233232,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
```

```json
{
  "name": "io_uring_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311488,
      "name": "io_uring_setup",
      "external": false,
      "loc": "fs/io_uring.c:3976",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_setup",
        "fs/io_uring.c:__x64_sys_io_uring_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311488,
      "name": "io_uring_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
long int io_uring_setup(u32 entries, struct io_uring_params * params)
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
