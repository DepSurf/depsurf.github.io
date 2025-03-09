# Function: <code>__kernel_read</code>

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
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076096,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:422",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076096,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:430",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339231,
      "name": "__kernel_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582121712,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:430",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281945,
      "name": "__kernel_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582144752,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
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
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:419",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592228881,
      "name": "__kernel_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582463328,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
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
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:416",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008428,
      "name": "__kernel_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582980896,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538848,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:404",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538848,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583754608,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:404",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "fs/verity/enable.c:build_merkle_tree",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754608,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
```

```json
{
  "name": "__kernel_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583957136,
      "name": "__kernel_read",
      "external": true,
      "loc": "fs/read_write.c:410",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:kernel_read",
        "fs/verity/enable.c:build_merkle_tree",
        "security/integrity/iint.c:integrity_kernel_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957136,
      "name": "__kernel_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
ssize_t __kernel_read(struct file * file, void * buf, size_t count, loff_t * pos)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
