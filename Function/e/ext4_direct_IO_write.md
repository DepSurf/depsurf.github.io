# Function: <code>ext4_direct_IO_write</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581776638,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3359",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581866490,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3492",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO"
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
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582015080,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3615",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO"
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
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582165438,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3656",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO"
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
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582354546,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3661",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO"
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
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582453665,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3694",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582622608,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3707",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622608,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723664,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723664,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494380656,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494380656,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227817880,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227817880,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1264
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288118048,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288118048,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1528
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
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273806824,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_direct_IO"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582692400,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692400,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582629568,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629568,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682256,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682256,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```

```json
{
  "name": "ext4_direct_IO_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582766400,
      "name": "ext4_direct_IO_write",
      "external": false,
      "loc": "fs/ext4/inode.c:3676",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766400,
      "name": "ext4_direct_IO_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1081
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
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb * iocb, struct iov_iter * iter)
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
