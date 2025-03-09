# Function: <code>io_uring_get_socket</code>

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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175408,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:374",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175408,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252656,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252656,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488656,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:905",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488656,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582546784,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:1034",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582546784,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575584,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:1072",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575584,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582893184,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:1111",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582893184,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585942704,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "io_uring/io_uring.c:1265",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942704,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586734672,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "io_uring/io_uring.c:156",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586734672,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586998336,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "io_uring/io_uring.c:155",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586998336,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493825560,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493825560,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227327632,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227327632,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287444240,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287444240,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273401254,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273401254,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221392,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221392,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159232,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159232,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211872,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211872,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
```

```json
{
  "name": "io_uring_get_socket",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582289904,
      "name": "io_uring_get_socket",
      "external": true,
      "loc": "fs/io_uring.c:375",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/scm.c:unix_get_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289904,
      "name": "io_uring_get_socket",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct sock * io_uring_get_socket(struct file * file)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct sock * io_uring_get_socket(struct file * file)
```
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
