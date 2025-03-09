# Function: <code>ksys_readahead</code>

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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943648,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:589",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943648,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019840,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:575",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019840,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581083856,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083856,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139840,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139840,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324848,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:635",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324848,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366752,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:611",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366752,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386224,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:611",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386224,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635344,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:613",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635344,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582000320,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:725",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582000320,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436480,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:735",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436480,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641888,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:734",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641888,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812992,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:719",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead",
        "arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812992,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492514304,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_readahead",
        "mm/readahead.c:__arm64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492514304,
      "name": "ksys_readahead",
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226384092,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__se_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226384092,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285804240,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sys_ppc32.c:compat_sys_readahead",
        "mm/readahead.c:__se_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285804240,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272571328,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__se_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272571328,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581108688,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108688,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055760,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055760,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099888,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099888,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
```

```json
{
  "name": "ksys_readahead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162144,
      "name": "ksys_readahead",
      "external": true,
      "loc": "mm/readahead.c:578",
      "file": "mm/readahead.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead",
        "arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead",
        "mm/readahead.c:__ia32_sys_readahead",
        "mm/readahead.c:__x64_sys_readahead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581162144,
      "name": "ksys_readahead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count)
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
