# Function: <code>__do_loopback</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581935968,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2253",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581935968,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582008608,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582008608,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245104,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2314",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245104,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294352,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2320",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294352,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582321472,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2349",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:__do_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321472,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641920,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2351",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:__do_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641920,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179184,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2392",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179184,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583754208,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2497",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754208,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971136,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2575",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971136,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183440,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2581",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:path_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183440,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493530680,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__arm64_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493530680,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227082672,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__se_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227082672,
      "name": "__do_loopback",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287098208,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__se_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287098208,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273197008,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:__se_sys_open_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273197008,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581977344,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977344,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581914912,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914912,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581968624,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581968624,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_loopback",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582039072,
      "name": "__do_loopback",
      "external": false,
      "loc": "fs/namespace.c:2256",
      "file": "fs/namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_mount",
        "fs/namespace.c:open_detached_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039072,
      "name": "__do_loopback.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct mount * __do_loopback(struct path * old_path, int recurse)
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
struct mount * __do_loopback(struct path * old_path, int recurse)
```
</details>
</li>
</ul>
