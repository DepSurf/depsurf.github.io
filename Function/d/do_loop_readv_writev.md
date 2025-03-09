# Function: <code>do_loop_readv_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t do_loop_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, io_fn_t fn)
```

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990496,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:695",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:do_readv_writev",
        "fs/read_write.c:compat_do_readv_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990496,
      "name": "do_loop_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
ssize_t do_loop_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, io_fn_t fn, int flags)
```

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145696,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:726",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145696,
      "name": "do_loop_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t do_loop_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, io_fn_t fn, int flags)
```

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220880,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:726",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:compat_do_readv_writev",
        "fs/read_write.c:do_readv_writev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220880,
      "name": "do_loop_readv_writev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581273779,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:681",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581412019,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:686",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581567393,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:713",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581653026,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:713",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581770914,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581843138,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582069491,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:755",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059040,
      "name": "do_loop_readv_writev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582116849,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:750",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108288,
      "name": "do_loop_readv_writev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582139953,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:748",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133232,
      "name": "do_loop_readv_writev.part.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582458481,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:739",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449888,
      "name": "do_loop_readv_writev.part.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582974746,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:750",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968752,
      "name": "do_loop_readv_writev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583532698,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:743",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528112,
      "name": "do_loop_readv_writev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583748309,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:743",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ],
      "caller_func": [
        "fs/read_write.c:do_iter_write",
        "fs/read_write.c:do_iter_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743536,
      "name": "do_loop_readv_writev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583951792,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:749",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv"
      ],
      "caller_func": [
        "fs/read_write.c:vfs_writev",
        "fs/read_write.c:vfs_readv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945184,
      "name": "do_loop_readv_writev.part.0",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493308224,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226910928,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286848960,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273049732,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581811874,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749538,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581803186,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
  "name": "do_loop_readv_writev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581872402,
      "name": "do_loop_readv_writev",
      "external": false,
      "loc": "fs/read_write.c:727",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:do_iter_read",
        "fs/read_write.c:do_iter_read"
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t do_loop_readv_writev(struct file * filp, struct iov_iter * iter, loff_t * ppos, io_fn_t fn, int flags)
```
</details>
</li>
</ul>
