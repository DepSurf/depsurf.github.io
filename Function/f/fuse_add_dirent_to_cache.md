# Function: <code>fuse_add_dirent_to_cache</code>

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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582948562,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583129138,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583235346,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562864,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562864,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675216,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675216,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583696224,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696224,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056352,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    },
    {
      "addr": 18446744071592289096,
      "name": "fuse_add_dirent_to_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647136,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071594071166,
      "name": "fuse_add_dirent_to_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328288,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
    },
    {
      "addr": 18446744071596091688,
      "name": "fuse_add_dirent_to_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585558272,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071596615052,
      "name": "fuse_add_dirent_to_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
```

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796688,
      "name": "fuse_add_dirent_to_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
    },
    {
      "addr": 18446744071597520935,
      "name": "fuse_add_dirent_to_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494958420,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228366020,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288835024,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274260636,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583204082,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583141234,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583188114,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
  "name": "fuse_add_dirent_to_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583282610,
      "name": "fuse_add_dirent_to_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:32",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
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
void fuse_add_dirent_to_cache(struct file * file, struct fuse_dirent * dirent, loff_t pos)
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
