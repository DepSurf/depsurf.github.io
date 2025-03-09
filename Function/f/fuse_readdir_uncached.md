# Function: <code>fuse_readdir_uncached</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582949485,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:296",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130496,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:296",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130496,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1118
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236704,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236704,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583565696,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565696,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678048,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678048,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583698800,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:320",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698800,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1297
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584059424,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:320",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059424,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1297
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647856,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:320",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647856,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585329056,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:322",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329056,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1338
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585559040,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:322",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585559040,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797456,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:330",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797456,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494960144,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494960144,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228367696,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228367696,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288837344,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288837344,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274261196,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274261196,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1698
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205440,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205440,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583142592,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583142592,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583189472,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583189472,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_uncached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583283312,
      "name": "fuse_readdir_uncached",
      "external": false,
      "loc": "fs/fuse/readdir.c:317",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583283312,
      "name": "fuse_readdir_uncached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
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
int fuse_readdir_uncached(struct file * file, struct dir_context * ctx)
```
</details>
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
