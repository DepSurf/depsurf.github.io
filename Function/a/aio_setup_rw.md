# Function: <code>aio_setup_rw</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int aio_setup_rw(int rw, struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564464,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1440",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564464,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int aio_setup_rw(int rw, struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621424,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1445",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621424,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int aio_setup_rw(int rw, struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766112,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1459",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766112,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int aio_setup_rw(int rw, struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933920,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1447",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933920,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
int aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018352,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1478",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018352,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154960,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154960,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232176,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232176,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582470608,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470608,
      "name": "aio_setup_rw.isra.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582527737,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1482",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
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
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582556536,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1479",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
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
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582872712,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
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
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583437002,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1505",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584026714,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1506",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584252861,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1498",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584470077,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1550",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493802104,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493802104,
      "name": "aio_setup_rw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227315068,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287421248,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287421248,
      "name": "aio_setup_rw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273390720,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582200912,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200912,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582138560,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138560,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191392,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191392,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```

```json
{
  "name": "aio_setup_rw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582268048,
      "name": "aio_setup_rw",
      "external": false,
      "loc": "fs/aio.c:1480",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:aio_write",
        "fs/aio.c:aio_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582268048,
      "name": "aio_setup_rw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int aio_setup_rw(int rw, struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t aio_setup_rw(int rw, const struct iocb * iocb, struct iovec * * iovec, bool vectored, bool compat, struct iov_iter * iter)
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
