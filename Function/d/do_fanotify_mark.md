# Function: <code>do_fanotify_mark</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894496,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:823",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894496,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1729
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981520,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:804",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981520,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115504,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:939",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115504,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1735
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192880,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192880,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433264,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1016",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433264,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488720,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1109",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488720,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1498
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516288,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1248",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516288,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1361
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582831264,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1356",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x64_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582831264,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393920,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1549",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393920,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1723
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583979776,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1589",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979776,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2055
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203744,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1651",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203744,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2180
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418064,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1739",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418064,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2358
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493754536,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__arm64_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493754536,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227277632,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287369952,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__se_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287369952,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1956
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
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273361010,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161616,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161616,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582099056,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099056,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152096,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152096,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```

```json
{
  "name": "do_fanotify_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226880,
      "name": "do_fanotify_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:947",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226880,
      "name": "do_fanotify_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char * pathname)
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
