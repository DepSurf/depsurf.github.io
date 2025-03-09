# Function: <code>ext4_dx_readdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581536878,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:508",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581722493,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:524",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581810159,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:525",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581882170,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:525",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582032231,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:526",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582220443,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:527",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582315308,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:527",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480864,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:527",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480864,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580064,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580064,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888752,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:532",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888752,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 941
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960992,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:530",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960992,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 941
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986896,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:549",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986896,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 941
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583322832,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:549",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322832,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1062
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583830960,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:548",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830960,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 960
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584454224,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:548",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454224,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 957
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584683104,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:548",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584683104,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584915872,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:548",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915872,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494229216,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494229216,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227661508,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287929852,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273684898,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582548800,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548800,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485968,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485968,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582538912,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582538912,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "ext4_dx_readdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620048,
      "name": "ext4_dx_readdir",
      "external": false,
      "loc": "fs/ext4/dir.c:534",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620048,
      "name": "ext4_dx_readdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ext4_dx_readdir(struct file * file, struct dir_context * ctx)
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
