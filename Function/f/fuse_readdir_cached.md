# Function: <code>fuse_readdir_cached</code>

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
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582949257,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:415",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583131695,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:415",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583237967,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583564592,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
      "addr": 18446744071583564592,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583676944,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
      "addr": 18446744071583676944,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1089
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583697712,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:434",
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
      "addr": 18446744071583697712,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1083
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:434",
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
      "addr": 18446744071584057856,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1561
    },
    {
      "addr": 18446744071592289125,
      "name": "fuse_readdir_cached.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:434",
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
      "addr": 18446744071584649184,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1878
    },
    {
      "addr": 18446744071594071193,
      "name": "fuse_readdir_cached.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:436",
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
      "addr": 18446744071585330416,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2106
    },
    {
      "addr": 18446744071596091715,
      "name": "fuse_readdir_cached.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:436",
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
      "addr": 18446744071585560416,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1988
    },
    {
      "addr": 18446744071596615079,
      "name": "fuse_readdir_cached.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:444",
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
      "addr": 18446744071585798832,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1905
    },
    {
      "addr": 18446744071597520962,
      "name": "fuse_readdir_cached.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494961272,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228368608,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
      "addr": 3228368608,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1940
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
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288838592,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
      "addr": 13835058055288838592,
      "name": "fuse_readdir_cached",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1924
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
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274263034,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583206703,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583143855,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583190735,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_readdir_cached",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583284580,
      "name": "fuse_readdir_cached",
      "external": false,
      "loc": "fs/fuse/readdir.c:431",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int fuse_readdir_cached(struct file * file, struct dir_context * ctx)
```
</details>
</li>
</ul>
