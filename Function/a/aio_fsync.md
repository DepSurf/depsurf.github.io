# Function: <code>aio_fsync</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581935584,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1575",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935584,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582020912,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1595",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020912,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582157568,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157568,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582234800,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234800,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582471136,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1600",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471136,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582528128,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1598",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528128,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582556944,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1595",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556944,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582873120,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1596",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873120,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583437456,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1620",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437456,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584027184,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1621",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027184,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584253360,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1613",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584253360,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584470576,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1656",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470576,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493803056,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493803056,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227314792,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227314792,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287422448,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287422448,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273390960,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273390960,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582203536,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203536,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582141184,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141184,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582194016,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194016,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int aio_fsync(struct fsync_iocb * req, const struct iocb * iocb, bool datasync)
```

```json
{
  "name": "aio_fsync",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582270912,
      "name": "aio_fsync",
      "external": false,
      "loc": "fs/aio.c:1597",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270912,
      "name": "aio_fsync",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int aio_fsync(struct fsync_iocb * req, struct iocb * iocb, bool datasync)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct iocb * iocb</code> ➡️ <code>const struct iocb * iocb</code>
</li>
</ul>
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
