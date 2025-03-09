# Function: <code>__io_uring_register</code>

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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582194864,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:3439",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194864,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275696,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275696,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582519968,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:8380",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582519968,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1066
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577008,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:10031",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577008,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1583
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638704,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:10021",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638704,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2920
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:10845",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966608,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3429
    },
    {
      "addr": 18446744071592238340,
      "name": "__io_uring_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_register",
      "external": false,
      "loc": "io_uring/io_uring.c:12582",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022384,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1959
    },
    {
      "addr": 18446744071594125504,
      "name": "__io_uring_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_register",
      "external": false,
      "loc": "io_uring/io_uring.c:4015",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759056,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1522
    },
    {
      "addr": 18446744071596111198,
      "name": "__io_uring_register.cold",
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_register",
      "external": false,
      "loc": "io_uring/io_uring.c:4341",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:__do_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025616,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1642
    },
    {
      "addr": 18446744071596635549,
      "name": "__io_uring_register.cold",
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_register",
      "external": false,
      "loc": "io_uring/register.c:389",
      "file": "io_uring/register.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/register.c:__do_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411984,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1611
    },
    {
      "addr": 18446744071597544803,
      "name": "__io_uring_register.cold",
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
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493841012,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_register"
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
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227350784,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_register"
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
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287474188,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_register"
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
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273420600,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_register"
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244432,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244432,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182160,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182160,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234912,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234912,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```

```json
{
  "name": "__io_uring_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313168,
      "name": "__io_uring_register",
      "external": false,
      "loc": "fs/io_uring.c:4009",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313168,
      "name": "__io_uring_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __io_uring_register(struct io_ring_ctx * ctx, unsigned int opcode, void * arg, unsigned int nr_args)
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
