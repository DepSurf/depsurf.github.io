# Function: <code>filemap_read</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t filemap_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t already_read)
```

```json
{
  "name": "filemap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344640,
      "name": "filemap_read",
      "external": true,
      "loc": "mm/filemap.c:2519",
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
      "addr": 18446744071581344640,
      "name": "filemap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 913
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
ssize_t filemap_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t already_read)
```

```json
{
  "name": "filemap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591936,
      "name": "filemap_read",
      "external": true,
      "loc": "mm/filemap.c:2600",
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
      "addr": 18446744071581591936,
      "name": "filemap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 983
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
ssize_t filemap_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t already_read)
```

```json
{
  "name": "filemap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_read",
      "external": true,
      "loc": "mm/filemap.c:2654",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "block/fops.c:blkdev_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964819,
      "name": "filemap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071581937664,
      "name": "filemap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
ssize_t filemap_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t already_read)
```

```json
{
  "name": "filemap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_read",
      "external": true,
      "loc": "mm/filemap.c:2661",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "block/fops.c:blkdev_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596024192,
      "name": "filemap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071582372816,
      "name": "filemap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
ssize_t filemap_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t already_read)
```

```json
{
  "name": "filemap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_read",
      "external": true,
      "loc": "mm/filemap.c:2626",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "block/fops.c:blkdev_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596546431,
      "name": "filemap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071582577744,
      "name": "filemap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
ssize_t filemap_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t already_read)
```

```json
{
  "name": "filemap_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filemap_read",
      "external": true,
      "loc": "mm/filemap.c:2561",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "block/fops.c:blkdev_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597450126,
      "name": "filemap_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071582747392,
      "name": "filemap_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
ssize_t filemap_read(struct kiocb * iocb, struct iov_iter * iter, ssize_t already_read)
```
</details>
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
