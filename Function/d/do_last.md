# Function: <code>do_last</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581051353,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3021",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581212041,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3211",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289578,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3175",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581338815,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3223",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581479876,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3221",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581640063,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3243",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581726475,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3257",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3255",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581845824,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2345
    },
    {
      "addr": 18446744071581859124,
      "name": "do_last.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581918336,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918336,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493399136,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493399136,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2268
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226985004,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226985004,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2460
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286955056,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286955056,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2860
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273111884,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273111884,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1768
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887072,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887072,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824672,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824672,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878384,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878384,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
```

```json
{
  "name": "do_last",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947888,
      "name": "do_last",
      "external": false,
      "loc": "fs/namei.c:3248",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947888,
      "name": "do_last",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
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
int do_last(struct nameidata * nd, struct file * file, const struct open_flags * op)
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
