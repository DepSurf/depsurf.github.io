# Function: <code>do_signalfd4</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581913792,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:262",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913792,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581997344,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:262",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997344,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582133904,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133904,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582211056,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211056,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582447744,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447744,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504416,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504416,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582532192,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:262",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532192,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848256,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:252",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__x64_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__x64_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848256,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583410080,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:253",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410080,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997168,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:253",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997168,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584221840,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:253",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584221840,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436384,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:253",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__ia32_compat_sys_signalfd",
        "fs/signalfd.c:__ia32_compat_sys_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436384,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493774216,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__arm64_compat_sys_signalfd",
        "fs/signalfd.c:__arm64_compat_sys_signalfd4",
        "fs/signalfd.c:__arm64_sys_signalfd",
        "fs/signalfd.c:__arm64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493774216,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227290000,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__se_sys_signalfd",
        "fs/signalfd.c:__se_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227290000,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287387280,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__se_compat_sys_signalfd",
        "fs/signalfd.c:__se_compat_sys_signalfd4",
        "fs/signalfd.c:__se_sys_signalfd",
        "fs/signalfd.c:__se_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287387280,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273370994,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:__se_sys_signalfd",
        "fs/signalfd.c:__se_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273370994,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582179792,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582179792,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582117424,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117424,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582170272,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170272,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int do_signalfd4(int ufd, sigset_t * mask, int flags)
```

```json
{
  "name": "do_signalfd4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582247248,
      "name": "do_signalfd4",
      "external": false,
      "loc": "fs/signalfd.c:263",
      "file": "fs/signalfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/signalfd.c:do_compat_signalfd4",
        "fs/signalfd.c:__ia32_sys_signalfd",
        "fs/signalfd.c:__x64_sys_signalfd",
        "fs/signalfd.c:__ia32_sys_signalfd4",
        "fs/signalfd.c:__x64_sys_signalfd4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247248,
      "name": "do_signalfd4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
int do_signalfd4(int ufd, sigset_t * mask, int flags)
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
