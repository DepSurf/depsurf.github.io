# Function: <code>iov_iter_pipe</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583432240,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:831",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432240,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583452960,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:957",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452960,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633056,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:959",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633056,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583850736,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1089",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850736,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583934544,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1143",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934544,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584112941,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132357,
      "name": "iov_iter_pipe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584112864,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584235760,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235760,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640368,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1191",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640368,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584759872,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1198",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584759872,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788272,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1300",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788272,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585219904,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1159",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219904,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586058448,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1211",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586058448,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587042656,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1029",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042656,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496110296,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496110296,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229435636,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229435636,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290359024,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290359024,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275176362,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275176362,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584204496,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204496,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584139712,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139712,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584188256,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188256,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
```

```json
{
  "name": "iov_iter_pipe",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584292688,
      "name": "iov_iter_pipe",
      "external": true,
      "loc": "lib/iov_iter.c:1157",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:generic_file_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292688,
      "name": "iov_iter_pipe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void iov_iter_pipe(struct iov_iter * i, int direction, struct pipe_inode_info * pipe, size_t count)
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
<code>int direction</code> ➡️ <code>unsigned int direction</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void iov_iter_pipe(struct iov_iter * i, unsigned int direction, struct pipe_inode_info * pipe, size_t count)
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
