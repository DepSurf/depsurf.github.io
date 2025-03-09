# Function: <code>generic_file_buffered_read</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580740402,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2053",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_file_read_iter"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869248,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2050",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869248,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2599
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940768,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2038",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940768,
      "name": "generic_file_buffered_read",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035248,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2029",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035248,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3059
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090816,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090816,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3073
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278432,
      "name": "generic_file_buffered_read",
      "external": true,
      "loc": "mm/filemap.c:1991",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278432,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2360
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581319488,
      "name": "generic_file_buffered_read",
      "external": true,
      "loc": "mm/filemap.c:2443",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319488,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1175
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492456624,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492456624,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2184
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226330832,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226330832,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2988
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285733424,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285733424,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3932
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272528334,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272528334,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2202
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059664,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059664,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3073
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006896,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006896,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3063
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050864,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050864,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3073
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```

```json
{
  "name": "generic_file_buffered_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112512,
      "name": "generic_file_buffered_read",
      "external": false,
      "loc": "mm/filemap.c:2009",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112512,
      "name": "generic_file_buffered_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2970
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
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
ssize_t generic_file_buffered_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t written)
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
