# Function: <code>open_detached_copy</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936464,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2326",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936464,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582009104,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582009104,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245616,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2387",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245616,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294864,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2393",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294864,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582322350,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2422",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_open_tree"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582642798,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2424",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_open_tree"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179776,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2465",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179776,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583754848,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2570",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754848,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971776,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2648",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971776,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184080,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2654",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184080,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493531728,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__arm64_sys_open_tree"
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
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227086164,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_open_tree"
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
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287099616,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_open_tree"
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
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273200778,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__se_sys_open_tree"
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977840,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977840,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915408,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915408,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581969120,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581969120,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct file * open_detached_copy(struct path * path, bool recursive)
```

```json
{
  "name": "open_detached_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039584,
      "name": "open_detached_copy",
      "external": false,
      "loc": "fs/namespace.c:2329",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_open_tree",
        "fs/namespace.c:__x64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039584,
      "name": "open_detached_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
struct file * open_detached_copy(struct path * path, bool recursive)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct file * open_detached_copy(struct path * path, bool recursive)
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
