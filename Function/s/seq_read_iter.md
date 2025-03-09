# Function: <code>seq_read_iter</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "seq_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seq_read_iter",
      "external": true,
      "loc": "fs/seq_file.c:168",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/kernfs/file.c:kernfs_fop_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591340007,
      "name": "seq_read_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071582308880,
      "name": "seq_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1307
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
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "seq_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seq_read_iter",
      "external": true,
      "loc": "fs/seq_file.c:171",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/kernfs/file.c:kernfs_fop_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282758,
      "name": "seq_read_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071582338480,
      "name": "seq_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1190
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
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "seq_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seq_read_iter",
      "external": true,
      "loc": "fs/seq_file.c:171",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/kernfs/file.c:kernfs_fop_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592230983,
      "name": "seq_read_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071582659008,
      "name": "seq_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1190
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
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "seq_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seq_read_iter",
      "external": true,
      "loc": "fs/seq_file.c:171",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/kernfs/file.c:kernfs_fop_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594010924,
      "name": "seq_read_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583199088,
      "name": "seq_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1149
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
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "seq_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583775280,
      "name": "seq_read_iter",
      "external": true,
      "loc": "fs/seq_file.c:171",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/kernfs/file.c:kernfs_fop_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583775280,
      "name": "seq_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1182
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
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "seq_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583992496,
      "name": "seq_read_iter",
      "external": true,
      "loc": "fs/seq_file.c:171",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/kernfs/file.c:kernfs_fop_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583992496,
      "name": "seq_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "seq_read_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205120,
      "name": "seq_read_iter",
      "external": true,
      "loc": "fs/seq_file.c:171",
      "file": "fs/seq_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/seq_file.c:seq_read",
        "fs/kernfs/file.c:kernfs_fop_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205120,
      "name": "seq_read_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1194
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
ssize_t seq_read_iter(struct kiocb * iocb, struct iov_iter * iter)
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
