# Function: <code>loop_rw_iter</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582257079,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255744,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t loop_rw_iter(int rw, struct file * file, struct kiocb * kiocb, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582498752,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:2530",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498752,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
ssize_t loop_rw_iter(int rw, struct io_kiocb * req, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582554080,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:3262",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554080,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
ssize_t loop_rw_iter(int rw, struct io_kiocb * req, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582272,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:3060",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582272,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
ssize_t loop_rw_iter(int rw, struct io_kiocb * req, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582899168,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:3282",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582899168,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
ssize_t loop_rw_iter(int rw, struct io_kiocb * req, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585957456,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "io_uring/io_uring.c:3818",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_write",
        "io_uring/io_uring.c:io_read",
        "io_uring/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585957456,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
ssize_t loop_rw_iter(int ddir, struct io_rw * rw, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586853488,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "io_uring/rw.c:429",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853488,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
ssize_t loop_rw_iter(int ddir, struct io_rw * rw, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587119632,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "io_uring/rw.c:429",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:io_read",
        "io_uring/rw.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587119632,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
ssize_t loop_rw_iter(int ddir, struct io_rw * rw, struct iov_iter * iter)
```

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587398352,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "io_uring/rw.c:480",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/rw.c:io_write",
        "io_uring/rw.c:__io_read",
        "io_uring/rw.c:__io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398352,
      "name": "loop_rw_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493829900,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493828664,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227332040,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227330900,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287450176,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287448640,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273404974,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273404060,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582225815,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224480,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582163655,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162320,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582216295,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214960,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "loop_rw_iter",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582294311,
      "name": "loop_rw_iter",
      "external": false,
      "loc": "fs/io_uring.c:1334",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ],
      "caller_func": [
        "fs/io_uring.c:io_write",
        "fs/io_uring.c:io_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582292992,
      "name": "loop_rw_iter.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
ssize_t loop_rw_iter(int rw, struct file * file, struct kiocb * kiocb, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_kiocb * req</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kiocb * kiocb</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, file, kiocb, iter</code> ➡️ <code>rw, req, iter</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ddir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_kiocb * req</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, req, iter</code> ➡️ <code>ddir, rw, iter</code>
</li>
<li>
<b>Param type changed. </b>
<code>int rw</code> ➡️ <code>struct io_rw * rw</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
