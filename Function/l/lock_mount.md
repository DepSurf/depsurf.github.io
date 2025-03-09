# Function: <code>lock_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581129248,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:1953",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:do_add_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:SyS_pivot_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129248,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295120,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:1962",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295120,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581373952,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2079",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581373952,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581429152,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2021",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581429152,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571040,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2086",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:SyS_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571040,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726352,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2117",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726352,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812880,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2041",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812880,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581932960,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2135",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932960,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582005600,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582005600,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582242656,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2196",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_new_mount_fc",
        "fs/namespace.c:do_move_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582242656,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291648,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2202",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount_fc",
        "fs/namespace.c:do_move_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291648,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582318752,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2244",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582318752,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639200,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2246",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639200,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176208,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2287",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176208,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750992,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2392",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount",
        "fs/namespace.c:do_move_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750992,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583984329,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2494",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584196873,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2500",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:__do_sys_pivot_root",
        "fs/namespace.c:path_mount",
        "fs/namespace.c:do_new_mount"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493526936,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__arm64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493526936,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227080312,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount",
        "fs/namespace.c:do_move_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227080312,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287093568,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287093568,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273193928,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__se_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273193928,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974336,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974336,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911904,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911904,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965616,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965616,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
struct mountpoint * lock_mount(struct path * path)
```

```json
{
  "name": "lock_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036096,
      "name": "lock_mount",
      "external": false,
      "loc": "fs/namespace.c:2138",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:__ia32_sys_pivot_root",
        "fs/namespace.c:__x64_sys_pivot_root",
        "fs/namespace.c:do_mount",
        "fs/namespace.c:do_add_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036096,
      "name": "lock_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct mountpoint * lock_mount(struct path * path)
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
