# Function: <code>fuse_dax_write_iter</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "fuse_dax_write_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583686272,
      "name": "fuse_dax_write_iter",
      "external": true,
      "loc": "fs/fuse/dax.c:744",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583686272,
      "name": "fuse_dax_write_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "fuse_dax_write_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583710800,
      "name": "fuse_dax_write_iter",
      "external": true,
      "loc": "fs/fuse/dax.c:744",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710800,
      "name": "fuse_dax_write_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 401
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
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "fuse_dax_write_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_write_iter",
      "external": true,
      "loc": "fs/fuse/dax.c:743",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592289287,
      "name": "fuse_dax_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584071376,
      "name": "fuse_dax_write_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "fuse_dax_write_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_write_iter",
      "external": true,
      "loc": "fs/fuse/dax.c:740",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594071354,
      "name": "fuse_dax_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584662576,
      "name": "fuse_dax_write_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "fuse_dax_write_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_write_iter",
      "external": true,
      "loc": "fs/fuse/dax.c:740",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596091826,
      "name": "fuse_dax_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585344672,
      "name": "fuse_dax_write_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "fuse_dax_write_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_write_iter",
      "external": true,
      "loc": "fs/fuse/dax.c:740",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596615190,
      "name": "fuse_dax_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585574736,
      "name": "fuse_dax_write_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "fuse_dax_write_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_dax_write_iter",
      "external": true,
      "loc": "fs/fuse/dax.c:740",
      "file": "fs/fuse/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597521073,
      "name": "fuse_dax_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585813136,
      "name": "fuse_dax_write_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
