# Function: <code>do_shmat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167824,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1086",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/compat.c:compat_SyS_shmat",
        "ipc/shm.c:SyS_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167824,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1232
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582383984,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1088",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_shmat",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/shm.c:SyS_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383984,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1243
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582476144,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1094",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_shmat",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/shm.c:SyS_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582476144,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1273
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557008,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1092",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:compat_SyS_shmat",
        "ipc/compat.c:compat_SyS_ipc",
        "ipc/shm.c:SyS_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557008,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1191
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582708928,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1282",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:compat_SyS_shmat",
        "ipc/shm.c:SyS_shmat",
        "ipc/syscall.c:compat_SyS_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708928,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1196
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582905024,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1363",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582905024,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1288
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583013424,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1392",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583013424,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1232
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195200,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195200,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301008,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301008,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583632144,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632144,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1262
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583752784,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1416",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583752784,
      "name": "do_shmat",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583776896,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1416",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583776896,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1422
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1512",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x64_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592291537,
      "name": "do_shmat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584139024,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1450
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1506",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594073762,
      "name": "do_shmat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071584736928,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1386
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1522",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596093456,
      "name": "do_shmat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585430880,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1377
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1522",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596616796,
      "name": "do_shmat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585661552,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1433
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1518",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597522676,
      "name": "do_shmat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071585908320,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1484
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495039792,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__arm64_compat_sys_shmat",
        "ipc/shm.c:__arm64_sys_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495039792,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228441132,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__se_sys_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228441132,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1240
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288926080,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__se_compat_sys_shmat",
        "ipc/shm.c:__se_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc",
        "ipc/syscall.c:ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288926080,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1632
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274316348,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__se_sys_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274316348,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269744,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269744,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583206880,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583206880,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583253776,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583253776,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
long int do_shmat(int shmid, char * shmaddr, int shmflg, ulong * raddr, long unsigned int shmlba)
```

```json
{
  "name": "do_shmat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583348256,
      "name": "do_shmat",
      "external": true,
      "loc": "ipc/shm.c:1418",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmat",
        "ipc/shm.c:__ia32_compat_sys_shmat",
        "ipc/shm.c:__ia32_sys_shmat",
        "ipc/shm.c:__x64_sys_shmat",
        "ipc/syscall.c:compat_ksys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583348256,
      "name": "do_shmat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
