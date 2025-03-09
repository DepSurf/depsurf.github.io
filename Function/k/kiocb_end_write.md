# Function: <code>kiocb_end_write</code>

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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582177365,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:870",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
      ],
      "caller_func": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177312,
      "name": "kiocb_end_write.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582253355,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582500166,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:1981",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw_common"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582557919,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:2638",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw_common"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582623970,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:2435",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw_iopoll"
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582955779,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:2636",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:kiocb_done",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw",
        "fs/io_uring.c:io_complete_rw"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kiocb_end_write(struct io_kiocb * req)
```

```json
{
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585965936,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "io_uring/io_uring.c:3162",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:__io_complete_rw_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585965936,
      "name": "kiocb_end_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586859649,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "io_uring/rw.c:223",
      "file": "io_uring/rw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_complete_rw_iopoll"
      ],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_complete_rw_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855104,
      "name": "kiocb_end_write.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587125907,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "io_uring/rw.c:223",
      "file": "io_uring/rw.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_complete_rw_iopoll"
      ],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_complete_rw_iopoll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587121392,
      "name": "kiocb_end_write.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
  "name": "kiocb_end_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583954434,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:2842",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_iocb_iter_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584482621,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:2842",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_complete_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619623,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:2842",
      "file": "fs/backing-file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/backing-file.c:backing_aio_rw_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587399749,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "include/linux/fs.h:2842",
      "file": "io_uring/rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493826488,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void kiocb_end_write(struct io_kiocb * req)
```

```json
{
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227329136,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227329136,
      "name": "kiocb_end_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287445252,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273401972,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582222091,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582159931,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582212571,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
  "name": "kiocb_end_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582290603,
      "name": "kiocb_end_write",
      "external": false,
      "loc": "fs/io_uring.c:939",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_complete_rw_iopoll",
        "fs/io_uring.c:io_complete_rw"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void kiocb_end_write(struct io_kiocb * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void kiocb_end_write(struct io_kiocb * req)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void kiocb_end_write(struct io_kiocb * req)
```
</details>
</li>
</ul>
