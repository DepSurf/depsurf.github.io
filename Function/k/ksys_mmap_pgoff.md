# Function: <code>ksys_mmap_pgoff</code>

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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581161568,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1543",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581161568,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241440,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1567",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241440,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315904,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1569",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315904,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375008,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375008,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581573712,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1553",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581573712,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581619296,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1591",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619296,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581641728,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1595",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__x32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641728,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1583",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__x64_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592200038,
      "name": "ksys_mmap_pgoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071581909632,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 685
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1595",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593976679,
      "name": "ksys_mmap_pgoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071582314912,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1419",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596032675,
      "name": "ksys_mmap_pgoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071582812048,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1368",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596554622,
      "name": "ksys_mmap_pgoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071583025552,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1395",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_compat_sys_ia32_mmap",
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597458727,
      "name": "ksys_mmap_pgoff.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071583208288,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492781208,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys.c:__arm64_sys_mmap",
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_mmap2",
        "mm/mmap.c:__arm64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492781208,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226597836,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:__se_sys_old_mmap",
        "mm/mmap.c:__se_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226597836,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286149504,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/syscalls.c:__se_sys_mmap",
        "arch/powerpc/kernel/syscalls.c:__se_sys_mmap2",
        "mm/mmap.c:__se_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286149504,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272753662,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/sys_riscv.c:__se_sys_mmap",
        "mm/mmap.c:__se_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272753662,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343856,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343856,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287568,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287568,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581335056,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581335056,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
```

```json
{
  "name": "ksys_mmap_pgoff",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399008,
      "name": "ksys_mmap_pgoff",
      "external": true,
      "loc": "mm/mmap.c:1577",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:__ia32_sys_mmap",
        "arch/x86/kernel/sys_x86_64.c:__x64_sys_mmap",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_mmap",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_mmap",
        "mm/mmap.c:__ia32_sys_mmap_pgoff",
        "mm/mmap.c:__x64_sys_mmap_pgoff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399008,
      "name": "ksys_mmap_pgoff",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
long unsigned int ksys_mmap_pgoff(long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int fd, long unsigned int pgoff)
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
