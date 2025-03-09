# Function: <code>fuse_read_args_fill</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583209481,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211696,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583537414,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:567",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539552,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583647270,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:590",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649360,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583667006,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:594",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583669920,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584026754,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:598",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028864,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584614692,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:607",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617200,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585294032,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:607",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585296688,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585524393,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:608",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585527024,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585761423,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:609",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_readahead",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585764144,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494929804,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494932040,
      "name": "fuse_read_args_fill",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228340732,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228341908,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288800364,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288803200,
      "name": "fuse_read_args_fill",
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
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274236514,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_send_readpages",
        "fs/fuse/file.c:fuse_do_readpage"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274238804,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583178217,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583180432,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583115369,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117584,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583162249,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164464,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```

```json
{
  "name": "fuse_read_args_fill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583255785,
      "name": "fuse_read_args_fill",
      "external": true,
      "loc": "fs/fuse/file.c:551",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
      ],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258016,
      "name": "fuse_read_args_fill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void fuse_read_args_fill(struct fuse_io_args * ia, struct file * file, loff_t pos, size_t count, int opcode)
```
</details>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
