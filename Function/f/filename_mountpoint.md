# Function: <code>filename_mountpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581058112,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2473",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058112,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581219008,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2687",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219008,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296704,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2651",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296704,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346272,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2696",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346272,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487664,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2694",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487664,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648062,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2690",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647728,
      "name": "filename_mountpoint.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581734334,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2709",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734000,
      "name": "filename_mountpoint.part.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850080,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2707",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850080,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581922576,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922576,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493403304,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493403304,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226989396,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226989396,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286960720,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286960720,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273115212,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273115212,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891312,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891312,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581828912,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828912,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882624,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882624,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```

```json
{
  "name": "filename_mountpoint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581952128,
      "name": "filename_mountpoint",
      "external": false,
      "loc": "fs/namei.c:2700",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:kern_path_mountpoint",
        "fs/namei.c:user_path_mountpoint_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581952128,
      "name": "filename_mountpoint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
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
int filename_mountpoint(int dfd, struct filename * name, struct path * path, unsigned int flags)
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
