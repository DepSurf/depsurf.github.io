# Function: <code>io_iopoll_check</code>

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
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182080,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:818",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_sq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182080,
      "name": "io_iopoll_check",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261200,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
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
      "addr": 18446744071582261200,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582535456,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:1930",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535456,
      "name": "io_iopoll_check.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
int io_iopoll_check(struct io_ring_ctx * ctx, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610944,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610944,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582652777,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:2389",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
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
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582974827,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:2586",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__do_sys_io_uring_enter"
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
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586016333,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "io_uring/io_uring.c:3105",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "io_uring/io_uring.c:1535",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773200,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    },
    {
      "addr": 18446744071596111398,
      "name": "io_iopoll_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int io_iopoll_check(struct io_ring_ctx * ctx, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "io_uring/io_uring.c:1615",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587041904,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071596635761,
      "name": "io_iopoll_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int io_iopoll_check(struct io_ring_ctx * ctx, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "io_uring/io_uring.c:1636",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587317024,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
    },
    {
      "addr": 18446744071597543463,
      "name": "io_iopoll_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493849664,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
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
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227350028,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
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
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287466308,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
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
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273419746,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229936,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
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
      "addr": 18446744071582229936,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167744,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
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
      "addr": 18446744071582167744,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582220416,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
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
      "addr": 18446744071582220416,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```

```json
{
  "name": "io_iopoll_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582306144,
      "name": "io_iopoll_check",
      "external": false,
      "loc": "fs/io_uring.c:889",
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
      "addr": 18446744071582306144,
      "name": "io_iopoll_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, long int min)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, long int min)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, long int min)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int io_iopoll_check(struct io_ring_ctx * ctx, unsigned int * nr_events, long int min)
```
</details>
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
