# Function: <code>ksys_fadvise64_64</code>

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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222624,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:30",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222624,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967536,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967536,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062640,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062640,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118416,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118416,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302160,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:191",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302160,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345376,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:192",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345376,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581364464,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:192",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364464,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612848,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:192",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612848,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973072,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:191",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973072,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582407632,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:191",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407632,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582613680,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:191",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582613680,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582785248,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:191",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64",
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fadvise64_64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582785248,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492487384,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_fadvise64_64",
        "mm/fadvise.c:__arm64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492487384,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226360512,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/sys_arm.c:sys_arm_fadvise64_64",
        "mm/fadvise.c:__se_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226360512,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285773824,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/syscalls.c:ppc_fadvise64_64",
        "arch/powerpc/kernel/sys_ppc32.c:ppc32_fadvise64",
        "mm/fadvise.c:__se_sys_fadvise64",
        "mm/fadvise.c:__se_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285773824,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272551582,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:__se_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272551582,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087264,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087264,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034448,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034448,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078464,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078464,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
```

```json
{
  "name": "ksys_fadvise64_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140352,
      "name": "ksys_fadvise64_64",
      "external": true,
      "loc": "mm/fadvise.c:193",
      "file": "mm/fadvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64",
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fadvise64_64",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fadvise64_64",
        "mm/fadvise.c:__ia32_sys_fadvise64",
        "mm/fadvise.c:__x64_sys_fadvise64",
        "mm/fadvise.c:__ia32_sys_fadvise64_64",
        "mm/fadvise.c:__x64_sys_fadvise64_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140352,
      "name": "ksys_fadvise64_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int ksys_fadvise64_64(int fd, loff_t offset, loff_t len, int advice)
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
