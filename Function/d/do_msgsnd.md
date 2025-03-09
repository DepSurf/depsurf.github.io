# Function: <code>do_msgsnd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582146928,
      "name": "do_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:609",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/compat.c:compat_SyS_msgsnd",
        "ipc/msg.c:SyS_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146928,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363008,
      "name": "do_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:609",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_msgsnd",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/msg.c:SyS_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363008,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1051
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454656,
      "name": "do_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:630",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_msgsnd",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/msg.c:SyS_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454656,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1088
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582533424,
      "name": "do_msgsnd",
      "external": true,
      "loc": "ipc/msg.c:630",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_msgsnd",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/msg.c:SyS_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533424,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582681648,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:734",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_SyS_msgsnd",
        "ipc/msg.c:SyS_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582681648,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1123
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875472,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:781",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875472,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985152,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:791",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985152,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1146
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164144,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:816",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164144,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270208,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270208,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583598448,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:840",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598448,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718816,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:840",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718816,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1309
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583743344,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:842",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743344,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1241
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:842",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x64_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105024,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
    },
    {
      "addr": 18446744071592290727,
      "name": "do_msgsnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:842",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702656,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1323
    },
    {
      "addr": 18446744071594072829,
      "name": "do_msgsnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:848",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394528,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071596092683,
      "name": "do_msgsnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:848",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625232,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071596616034,
      "name": "do_msgsnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:848",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585871952,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1357
    },
    {
      "addr": 18446744071597521938,
      "name": "do_msgsnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495002096,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgsnd",
        "ipc/msg.c:ksys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495002096,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228415940,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:ksys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228415940,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288883936,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_ksys_msgsnd",
        "ipc/msg.c:ksys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288883936,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274292862,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:ksys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274292862,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238944,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238944,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176096,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176096,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583222976,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583222976,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1194
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
long int do_msgsnd(int msqid, long int mtype, void * mtext, size_t msgsz, int msgflg)
```

```json
{
  "name": "do_msgsnd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320912,
      "name": "do_msgsnd",
      "external": false,
      "loc": "ipc/msg.c:817",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_compat_sys_msgsnd",
        "ipc/msg.c:__ia32_sys_msgsnd",
        "ipc/msg.c:__x64_sys_msgsnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320912,
      "name": "do_msgsnd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1224
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
