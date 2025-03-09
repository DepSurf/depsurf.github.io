# Function: <code>warn_unsupported</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int warn_unsupported(struct file * file, const char * op)
```

```json
{
  "name": "warn_unsupported",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582111356,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/read_write.c:422",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ]
    },
    {
      "addr": 18446744071582371472,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/splice.c:748",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/splice.c:do_splice_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339156,
      "name": "warn_unsupported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582371472,
      "name": "warn_unsupported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int warn_unsupported(struct file * file, const char * op)
```

```json
{
  "name": "warn_unsupported",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582136295,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/read_write.c:422",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ]
    },
    {
      "addr": 18446744071582398784,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/splice.c:751",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/splice.c:do_splice_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591281870,
      "name": "warn_unsupported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582398784,
      "name": "warn_unsupported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int warn_unsupported(struct file * file, const char * op)
```

```json
{
  "name": "warn_unsupported",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582452922,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/read_write.c:411",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ]
    },
    {
      "addr": 18446744071582720320,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/splice.c:751",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/splice.c:do_splice_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592228806,
      "name": "warn_unsupported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071582720320,
      "name": "warn_unsupported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int warn_unsupported(struct file * file, const char * op)
```

```json
{
  "name": "warn_unsupported",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582974059,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/read_write.c:408",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read"
      ]
    },
    {
      "addr": 18446744071583265024,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/splice.c:751",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/splice.c:do_splice_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008343,
      "name": "warn_unsupported.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583265024,
      "name": "warn_unsupported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int warn_unsupported(struct file * file, const char * op)
```

```json
{
  "name": "warn_unsupported",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583541462,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/read_write.c:396",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:__kernel_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583846848,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/splice.c:748",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor",
        "fs/splice.c:do_splice_to"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846848,
      "name": "warn_unsupported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int warn_unsupported(struct file * file, const char * op)
```

```json
{
  "name": "warn_unsupported",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583757351,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/read_write.c:396",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:__kernel_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065024,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/splice.c:920",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:direct_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065024,
      "name": "warn_unsupported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int warn_unsupported(struct file * file, const char * op)
```

```json
{
  "name": "warn_unsupported",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959974,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/read_write.c:402",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:__kernel_write_iter",
        "fs/read_write.c:__kernel_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584280304,
      "name": "warn_unsupported",
      "external": false,
      "loc": "fs/splice.c:925",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:do_splice",
        "fs/splice.c:splice_file_range_actor",
        "fs/splice.c:direct_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280304,
      "name": "warn_unsupported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int warn_unsupported(struct file * file, const char * op)
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
