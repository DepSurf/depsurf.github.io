# Function: <code>ext4_dio_write_iter</code>

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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948192,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:454",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948192,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583022208,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:455",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022208,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047536,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:471",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047536,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1279
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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:471",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385328,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
    },
    {
      "addr": 18446744071592255046,
      "name": "ext4_dio_write_iter.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:471",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899184,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
    },
    {
      "addr": 18446744071594036029,
      "name": "ext4_dio_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:486",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524592,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1198
    },
    {
      "addr": 18446744071596069225,
      "name": "ext4_dio_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:532",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584753840,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 990
    },
    {
      "addr": 18446744071596593043,
      "name": "ext4_dio_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dio_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:498",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986592,
      "name": "ext4_dio_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 967
    },
    {
      "addr": 18446744071597498606,
      "name": "ext4_dio_write_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
ssize_t ext4_dio_write_iter(struct kiocb * iocb, struct iov_iter * from)
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
