# Function: <code>ksys_sync_file_range</code>

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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804640,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:285",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804640,
      "name": "ksys_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891648,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:285",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891648,
      "name": "ksys_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017008,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017008,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094960,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094960,
      "name": "ksys_sync_file_range",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332382,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:368",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332608,
      "name": "ksys_sync_file_range",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582383806,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:368",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384032,
      "name": "ksys_sync_file_range",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582411214,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:367",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411312,
      "name": "ksys_sync_file_range",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582733598,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:368",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733696,
      "name": "ksys_sync_file_range",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583279038,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:355",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279168,
      "name": "ksys_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583861838,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:355",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861984,
      "name": "ksys_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584083598,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:355",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083744,
      "name": "ksys_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584299710,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:355",
      "file": "fs/sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584299856,
      "name": "ksys_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493631072,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_sync_file_range2",
        "fs/sync.c:__arm64_sys_sync_file_range2",
        "fs/sync.c:__arm64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493631072,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227171344,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__se_sys_sync_file_range2",
        "fs/sync.c:__se_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227171344,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287221952,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sys_ppc32.c:compat_sys_sync_file_range2",
        "fs/sync.c:__se_sys_sync_file_range2",
        "fs/sync.c:__se_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287221952,
      "name": "ksys_sync_file_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273270974,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:__se_sys_sync_file_range2",
        "fs/sync.c:__se_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273270974,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063696,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063696,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582001248,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001248,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054976,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054976,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
```

```json
{
  "name": "ksys_sync_file_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126656,
      "name": "ksys_sync_file_range",
      "external": true,
      "loc": "fs/sync.c:365",
      "file": "fs/sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range",
        "fs/sync.c:__ia32_sys_sync_file_range2",
        "fs/sync.c:__x64_sys_sync_file_range2",
        "fs/sync.c:__ia32_sys_sync_file_range",
        "fs/sync.c:__x64_sys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126656,
      "name": "ksys_sync_file_range",
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags)
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
