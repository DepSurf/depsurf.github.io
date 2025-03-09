# Function: <code>inotify_update_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581279482,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:617",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581445309,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:617",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581526125,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:617",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581578993,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:585",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581723393,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:585",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581889408,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:603",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581889408,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975360,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:610",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975360,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582108880,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:599",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582108880,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186256,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186256,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582423984,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423984,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478000,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:615",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478000,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504816,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:614",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504816,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582820016,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:619",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582820016,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374704,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:639",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374704,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583959792,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:639",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959792,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183200,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:639",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584183200,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397184,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:638",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397184,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493747856,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch"
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227269168,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch"
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287357088,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch"
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
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273353258,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch"
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154992,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154992,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092432,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092432,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145472,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145472,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```

```json
{
  "name": "inotify_update_watch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218768,
      "name": "inotify_update_watch",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:608",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch",
        "fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218768,
      "name": "inotify_update_watch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```
</details>
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
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int inotify_update_watch(struct fsnotify_group * group, struct inode * inode, u32 arg)
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
