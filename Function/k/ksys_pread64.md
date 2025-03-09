# Function: <code>ksys_pread64</code>

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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577280,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:639",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577280,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581663040,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:639",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663040,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780160,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780160,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852384,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852384,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582065739,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:680",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077120,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582112315,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:675",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123072,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582146267,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:673",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147952,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582454155,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:664",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464784,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582982519,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:659",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984416,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583540871,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583544592,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583756727,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583760544,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959287,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:658",
      "file": "fs/read_write.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_pread64",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963232,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493319544,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_pread64",
        "fs/read_write.c:__arm64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493319544,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226915628,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226915628,
      "name": "ksys_pread64",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286859344,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sys_ppc32.c:compat_sys_pread64",
        "fs/read_write.c:__se_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286859344,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273053266,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/read_write.c:__se_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273053266,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581821120,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581821120,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758784,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758784,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581812432,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812432,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
```

```json
{
  "name": "ksys_pread64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881648,
      "name": "ksys_pread64",
      "external": true,
      "loc": "fs/read_write.c:652",
      "file": "fs/read_write.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_pread",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_pread",
        "fs/read_write.c:__ia32_sys_pread64",
        "fs/read_write.c:__x64_sys_pread64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881648,
      "name": "ksys_pread64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
ssize_t ksys_pread64(unsigned int fd, char * buf, size_t count, loff_t pos)
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
