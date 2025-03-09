# Function: <code>ksys_fallocate</code>

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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556464,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:340",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556464,
      "name": "ksys_fallocate",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581641952,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:329",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581641952,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758672,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758672,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830880,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830880,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582049726,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:327",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582051616,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582099310,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:327",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101600,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124126,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:328",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126448,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440990,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:325",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443088,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582958606,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:340",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961072,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583516926,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:340",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519616,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583732446,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:341",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735056,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583933230,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:345",
      "file": "fs/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_fallocate",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936080,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493294176,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_fallocate",
        "fs/open.c:__arm64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493294176,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226897396,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__se_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226897396,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286832224,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sys_ppc32.c:compat_sys_fallocate",
        "fs/open.c:__se_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286832224,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273039188,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:__se_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273039188,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799616,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799616,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581737280,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581737280,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790928,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790928,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
```

```json
{
  "name": "ksys_fallocate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860064,
      "name": "ksys_fallocate",
      "external": true,
      "loc": "fs/open.c:330",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_fallocate",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_fallocate",
        "fs/open.c:__ia32_sys_fallocate",
        "fs/open.c:__x64_sys_fallocate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860064,
      "name": "ksys_fallocate",
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
int ksys_fallocate(int fd, int mode, loff_t offset, loff_t len)
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
