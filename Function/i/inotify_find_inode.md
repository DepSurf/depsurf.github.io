# Function: <code>inotify_find_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581279341,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:332",
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581445165,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:332",
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581525981,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:332",
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581578845,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:330",
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581723245,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:330",
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888384,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:344",
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
      "addr": 18446744071581888384,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973360,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:345",
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
      "addr": 18446744071581973360,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106832,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:334",
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
      "addr": 18446744071582106832,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582184096,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
      "addr": 18446744071582184096,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582422048,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
      "addr": 18446744071582422048,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582476032,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:346",
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
      "addr": 18446744071582476032,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502896,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:345",
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
      "addr": 18446744071582502896,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817952,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:350",
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
      "addr": 18446744071582817952,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375168,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:373",
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
      "addr": 18446744071583375168,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960272,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:373",
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
      "addr": 18446744071583960272,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584183680,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:373",
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
      "addr": 18446744071584183680,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397664,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:372",
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
      "addr": 18446744071584397664,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493747704,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227269008,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287356852,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273353144,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152832,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
      "addr": 18446744071582152832,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582090272,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
      "addr": 18446744071582090272,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582143312,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
      "addr": 18446744071582143312,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```

```json
{
  "name": "inotify_find_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217968,
      "name": "inotify_find_inode",
      "external": false,
      "loc": "fs/notify/inotify/inotify_user.c:335",
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
      "addr": 18446744071582217968,
      "name": "inotify_find_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags)
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u64 mask</code>
</li>
</ul>
</details>
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
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int inotify_find_inode(const char * dirname, struct path * path, unsigned int flags, __u64 mask)
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
