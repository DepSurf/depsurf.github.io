# Function: <code>__do_sys_io_uring_enter</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582188625,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3172",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582268525,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const sigset_t * sig, size_t sigsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551856,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:7892",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551856,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void * argp, size_t argsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582622384,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:9346",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622384,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1035
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
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void * argp, size_t argsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582651760,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:9318",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651760,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1417
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
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void * argp, size_t argsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582973824,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:9994",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973824,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1414
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
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void * argp, size_t argsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586015440,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "io_uring/io_uring.c:11538",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_enter",
        "io_uring/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586015440,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1663
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
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void * argp, size_t argsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "io_uring/io_uring.c:3282",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_enter",
        "io_uring/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783104,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1203
    },
    {
      "addr": 18446744071596111576,
      "name": "__do_sys_io_uring_enter.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void * argp, size_t argsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "io_uring/io_uring.c:3568",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_enter",
        "io_uring/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048480,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
    },
    {
      "addr": 18446744071596635933,
      "name": "__do_sys_io_uring_enter.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void * argp, size_t argsz)
```

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "io_uring/io_uring.c:3591",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_enter",
        "io_uring/io_uring.c:__x64_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323680,
      "name": "__do_sys_io_uring_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
    },
    {
      "addr": 18446744071597543635,
      "name": "__do_sys_io_uring_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493849112,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227349444,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter"
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287465560,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter"
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273419528,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter"
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582237261,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582175005,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582227741,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
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
  "name": "__do_sys_io_uring_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582308061,
      "name": "__do_sys_io_uring_enter",
      "external": false,
      "loc": "fs/io_uring.c:3725",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const sigset_t * sig, size_t sigsz)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * argp</code>
</li>
<li>
<b>Param added. </b>
<code>size_t argsz</code>
</li>
<li>
<b>Param removed. </b>
<code>const sigset_t * sig</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t sigsz</code>
</li>
</ul>
</details>
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
