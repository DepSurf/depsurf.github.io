# Function: <code>__do_compat_sys_vmsplice</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799776,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1371",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799776,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886912,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1375",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886912,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012992,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1381",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012992,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090960,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1389",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090960,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324224,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1377",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324224,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493623224,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1389",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__arm64_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493623224,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287217216,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1389",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__se_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287217216,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059696,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1389",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059696,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997248,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1389",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997248,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582050976,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1389",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050976,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```

```json
{
  "name": "__do_compat_sys_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582122656,
      "name": "__do_compat_sys_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1389",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__x32_compat_sys_vmsplice",
        "fs/splice.c:__ia32_compat_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122656,
      "name": "__do_compat_sys_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_vmsplice(int fd, const struct compat_iovec * iov32, unsigned int nr_segs, unsigned int flags)
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
