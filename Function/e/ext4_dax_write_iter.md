# Function: <code>ext4_dax_write_iter</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581816018,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:174",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581932469,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:181",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582081770,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:184",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582269584,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:184",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582368241,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:184",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582536874,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:188",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582637768,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945552,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:592",
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
      "addr": 18446744071582945552,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020304,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:597",
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
      "addr": 18446744071583020304,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583046112,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:613",
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
      "addr": 18446744071583046112,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583383408,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:613",
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
      "addr": 18446744071583383408,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583896816,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:612",
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
      "addr": 18446744071583896816,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522944,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:633",
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
      "addr": 18446744071584522944,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584752160,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:655",
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
      "addr": 18446744071584752160,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584984912,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:629",
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
      "addr": 18446744071584984912,
      "name": "ext4_dax_write_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494289984,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288003536,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273733050,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582606504,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582543672,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582596616,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dax_write_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582678680,
      "name": "ext4_dax_write_iter",
      "external": false,
      "loc": "fs/ext4/file.c:189",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_file_write_iter"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb * iocb, struct iov_iter * from)
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
