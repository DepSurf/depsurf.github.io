# Function: <code>fanotify_remove_mark</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980928,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:526",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980928,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582115248,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:596",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115248,
      "name": "fanotify_remove_mark",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192624,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192624,
      "name": "fanotify_remove_mark",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432384,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:673",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432384,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags, __u32 umask)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582487824,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:746",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487824,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags, __u32 umask)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582515328,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:839",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582515328,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags, __u32 umask)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830576,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:939",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830576,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags, __u32 umask)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583392032,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1030",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392032,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags, __u32 umask)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583977680,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1030",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977680,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags, __u32 umask)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201008,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1079",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201008,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags, __u32 umask)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584415536,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1078",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415536,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493753728,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493753728,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227273404,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227273404,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287369504,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287369504,
      "name": "fanotify_remove_mark",
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273358014,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273358014,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161360,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161360,
      "name": "fanotify_remove_mark",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098800,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098800,
      "name": "fanotify_remove_mark",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151840,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151840,
      "name": "fanotify_remove_mark",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```

```json
{
  "name": "fanotify_remove_mark",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224656,
      "name": "fanotify_remove_mark",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:604",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark",
        "fs/notify/fanotify/fanotify_user.c:do_fanotify_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224656,
      "name": "fanotify_remove_mark",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int fanotify_remove_mark(struct fsnotify_group * group, fsnotify_connp_t * connp, __u32 mask, unsigned int flags)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u32 umask</code>
</li>
</ul>
</details>
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
