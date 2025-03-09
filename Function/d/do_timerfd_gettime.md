# Function: <code>do_timerfd_gettime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304272,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:482",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:SyS_timerfd_gettime",
        "fs/timerfd.c:compat_SyS_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304272,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int do_timerfd_gettime(int ufd, struct itimerspec * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470416,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:492",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_gettime",
        "fs/timerfd.c:SyS_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470416,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int do_timerfd_gettime(int ufd, struct itimerspec * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551104,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:492",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_gettime",
        "fs/timerfd.c:SyS_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551104,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int do_timerfd_gettime(int ufd, struct itimerspec * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605008,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:502",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_gettime",
        "fs/timerfd.c:SyS_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605008,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
int do_timerfd_gettime(int ufd, struct itimerspec * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749168,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:503",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_gettime",
        "fs/timerfd.c:SyS_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749168,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917296,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:503",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__x32_compat_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_compat_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917296,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582001920,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:503",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__x32_compat_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_compat_sys_timerfd_gettime",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001920,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582140240,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:503",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582140240,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217392,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217392,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451648,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:510",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451648,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582508336,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:510",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582508336,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582536112,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:510",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536112,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582852144,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:526",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582852144,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583416272,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:526",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416272,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584003744,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:526",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003744,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228416,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:526",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228416,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584442976,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:526",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442976,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493779152,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__arm64_sys_timerfd_gettime32",
        "fs/timerfd.c:__arm64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493779152,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227294084,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_gettime32",
        "fs/timerfd.c:__se_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227294084,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287395520,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_gettime32",
        "fs/timerfd.c:__se_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287395520,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
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
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273375780,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__se_sys_timerfd_gettime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582186128,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582186128,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123696,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123696,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176608,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176608,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
```

```json
{
  "name": "do_timerfd_gettime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249520,
      "name": "do_timerfd_gettime",
      "external": false,
      "loc": "fs/timerfd.c:507",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_gettime32",
        "fs/timerfd.c:__x64_sys_timerfd_gettime32",
        "fs/timerfd.c:__ia32_sys_timerfd_gettime",
        "fs/timerfd.c:__x64_sys_timerfd_gettime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249520,
      "name": "do_timerfd_gettime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct itimerspec * t</code> ➡️ <code>struct itimerspec64 * t</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_timerfd_gettime(int ufd, struct itimerspec64 * t)
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
