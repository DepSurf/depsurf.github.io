# Function: <code>do_msgrcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147984,
      "name": "do_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:825",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/compat.c:compat_SyS_msgrcv",
        "ipc/msg.c:SyS_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147984,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1429
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364128,
      "name": "do_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:825",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_msgrcv",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/msg.c:SyS_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364128,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1431
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582455808,
      "name": "do_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:849",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_msgrcv",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/msg.c:SyS_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582455808,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1437
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534576,
      "name": "do_msgrcv",
      "external": true,
      "loc": "ipc/msg.c:849",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_msgrcv",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/msg.c:SyS_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534576,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1494
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582682784,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:972",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:compat_SyS_msgrcv",
        "ipc/msg.c:SyS_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582682784,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1463
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582877424,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1031",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877424,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1413
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983536,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1041",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983536,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1413
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583167632,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1066",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167632,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1538
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583273648,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273648,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1538
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601520,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1090",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601520,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1682
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583721872,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1090",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721872,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746304,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1092",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746304,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1655
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1092",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x64_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584108000,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1669
    },
    {
      "addr": 18446744071592290781,
      "name": "do_msgrcv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1092",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704320,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1790
    },
    {
      "addr": 18446744071594072887,
      "name": "do_msgrcv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1098",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396288,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1853
    },
    {
      "addr": 18446744071596092725,
      "name": "do_msgrcv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1098",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626992,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
    },
    {
      "addr": 18446744071596616076,
      "name": "do_msgrcv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1098",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585873712,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
    },
    {
      "addr": 18446744071597521980,
      "name": "do_msgrcv.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495003712,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__arm64_compat_sys_msgrcv",
        "ipc/msg.c:__arm64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495003712,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1332
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
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228414160,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228414160,
      "name": "do_msgrcv.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288888304,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_compat_sys_msgrcv",
        "ipc/msg.c:__se_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288888304,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1868
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
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274295040,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__se_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274295040,
      "name": "do_msgrcv.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1216
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242384,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242384,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1538
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583179536,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179536,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1538
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226416,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226416,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1538
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
```

```json
{
  "name": "do_msgrcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583319136,
      "name": "do_msgrcv",
      "external": false,
      "loc": "ipc/msg.c:1067",
      "file": "ipc/msg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/msg.c:__x32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_compat_sys_msgrcv",
        "ipc/msg.c:__ia32_sys_msgrcv",
        "ipc/msg.c:__x64_sys_msgrcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583319136,
      "name": "do_msgrcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
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
long int do_msgrcv(int msqid, void * buf, size_t bufsz, long int msgtyp, int msgflg, long int (*)(void *, struct msg_msg *, size_t) msg_handler)
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
