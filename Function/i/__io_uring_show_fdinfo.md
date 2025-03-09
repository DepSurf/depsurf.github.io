# Function: <code>__io_uring_show_fdinfo</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```

```json
{
  "name": "__io_uring_show_fdinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513536,
      "name": "__io_uring_show_fdinfo",
      "external": false,
      "loc": "fs/io_uring.c:7999",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513536,
      "name": "__io_uring_show_fdinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```

```json
{
  "name": "__io_uring_show_fdinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571824,
      "name": "__io_uring_show_fdinfo",
      "external": false,
      "loc": "fs/io_uring.c:9475",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571824,
      "name": "__io_uring_show_fdinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```

```json
{
  "name": "__io_uring_show_fdinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582612672,
      "name": "__io_uring_show_fdinfo",
      "external": false,
      "loc": "fs/io_uring.c:9446",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582612672,
      "name": "__io_uring_show_fdinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
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
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```

```json
{
  "name": "__io_uring_show_fdinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_show_fdinfo",
      "external": false,
      "loc": "fs/io_uring.c:10122",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922784,
      "name": "__io_uring_show_fdinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
    },
    {
      "addr": 18446744071592237679,
      "name": "__io_uring_show_fdinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```

```json
{
  "name": "__io_uring_show_fdinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594114630,
      "name": "__io_uring_show_fdinfo",
      "external": false,
      "loc": "io_uring/io_uring.c:11706",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594114630,
      "name": "__io_uring_show_fdinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1295
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
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```

```json
{
  "name": "__io_uring_show_fdinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_show_fdinfo",
      "external": false,
      "loc": "io_uring/fdinfo.c:51",
      "file": "io_uring/fdinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/fdinfo.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820528,
      "name": "__io_uring_show_fdinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1870
    },
    {
      "addr": 18446744071596111881,
      "name": "__io_uring_show_fdinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```

```json
{
  "name": "__io_uring_show_fdinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__io_uring_show_fdinfo",
      "external": false,
      "loc": "io_uring/fdinfo.c:49",
      "file": "io_uring/fdinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/fdinfo.c:io_uring_show_fdinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587087040,
      "name": "__io_uring_show_fdinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1894
    },
    {
      "addr": 18446744071596636299,
      "name": "__io_uring_show_fdinfo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```
</details>
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
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx * ctx, struct seq_file * m)
```
</details>
</li>
</ul>
