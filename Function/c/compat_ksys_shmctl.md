# Function: <code>compat_ksys_shmctl</code>

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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582904240,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1293",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582904240,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 714
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012576,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1322",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl",
        "ipc/syscall.c:__x32_compat_sys_ipc",
        "ipc/syscall.c:__ia32_compat_sys_ipc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012576,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194208,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194208,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300016,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300016,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629312,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629312,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583749920,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1334",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749920,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774112,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1334",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774112,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584136208,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1430",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x64_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x64_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136208,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584734512,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1424",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734512,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585428256,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1440",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585428256,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585658976,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1440",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585658976,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585905744,
      "name": "compat_ksys_shmctl",
      "external": false,
      "loc": "ipc/shm.c:1436",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585905744,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495038760,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__arm64_compat_sys_old_shmctl",
        "ipc/shm.c:__arm64_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495038760,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288925072,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__se_compat_sys_old_shmctl",
        "ipc/shm.c:__se_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288925072,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268752,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268752,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205888,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205888,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252784,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252784,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
```

```json
{
  "name": "compat_ksys_shmctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583347264,
      "name": "compat_ksys_shmctl",
      "external": true,
      "loc": "ipc/shm.c:1335",
      "file": "ipc/shm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/shm.c:__x32_compat_sys_old_shmctl",
        "ipc/shm.c:__ia32_compat_sys_old_shmctl",
        "ipc/shm.c:__x32_compat_sys_shmctl",
        "ipc/shm.c:__ia32_compat_sys_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347264,
      "name": "compat_ksys_shmctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int version</code>
</li>
</ul>
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
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
long int compat_ksys_shmctl(int shmid, int cmd, void * uptr, int version)
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
