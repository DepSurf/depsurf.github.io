# Function: <code>do_timerfd_settime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec * new, struct itimerspec * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304656,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:418",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:SyS_timerfd_settime",
        "fs/timerfd.c:compat_SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304656,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec * new, struct itimerspec * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581470800,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:423",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581470800,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec * new, struct itimerspec * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551488,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:423",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551488,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec * new, struct itimerspec * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605392,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:434",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605392,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec * new, struct itimerspec * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749552,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:compat_SyS_timerfd_settime",
        "fs/timerfd.c:SyS_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749552,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581918368,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__x32_compat_sys_timerfd_settime",
        "fs/timerfd.c:__ia32_compat_sys_timerfd_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918368,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582002736,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__x32_compat_sys_timerfd_settime",
        "fs/timerfd.c:__ia32_compat_sys_timerfd_settime",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002736,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582138480,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582138480,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
    },
    {
      "addr": 18446744071582139536,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215632,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215632,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
    },
    {
      "addr": 18446744071582216688,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452816,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:438",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452816,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1291
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582509520,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:438",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582509520,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1295
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582537296,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:438",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582537296,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1295
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:454",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582853072,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1234
    },
    {
      "addr": 18446744071592236539,
      "name": "do_timerfd_settime.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:454",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412288,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1273
    },
    {
      "addr": 18446744071594016682,
      "name": "do_timerfd_settime.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:454",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999568,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1273
    },
    {
      "addr": 18446744071596056368,
      "name": "do_timerfd_settime.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:454",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584224240,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1276
    },
    {
      "addr": 18446744071596580542,
      "name": "do_timerfd_settime.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:454",
      "file": "fs/timerfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438832,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1276
    },
    {
      "addr": 18446744071597484459,
      "name": "do_timerfd_settime.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493779864,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__arm64_sys_timerfd_settime32",
        "fs/timerfd.c:__arm64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493779864,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
    },
    {
      "addr": 18446603336493781112,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227294532,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_settime32",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227294532,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
    },
    {
      "addr": 3227295664,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287393424,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__se_sys_timerfd_settime32",
        "fs/timerfd.c:__se_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287393424,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1524
    },
    {
      "addr": 13835058055287394960,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273374692,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/timerfd.c:__se_sys_timerfd_settime"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582184368,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184368,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
    },
    {
      "addr": 18446744071582185424,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582121952,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121952,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1033
    },
    {
      "addr": 18446744071582122992,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582174848,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582174848,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
    },
    {
      "addr": 18446744071582175904,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
```

```json
{
  "name": "do_timerfd_settime",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582251408,
      "name": "do_timerfd_settime",
      "external": false,
      "loc": "fs/timerfd.c:435",
      "file": "fs/timerfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/timerfd.c:__ia32_sys_timerfd_settime32",
        "fs/timerfd.c:__x64_sys_timerfd_settime32",
        "fs/timerfd.c:__ia32_sys_timerfd_settime",
        "fs/timerfd.c:__x64_sys_timerfd_settime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582251408,
      "name": "do_timerfd_settime.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
    },
    {
      "addr": 18446744071582252432,
      "name": "do_timerfd_settime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
<code>const struct itimerspec * new</code> ➡️ <code>const struct itimerspec64 * new</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct itimerspec * old</code> ➡️ <code>struct itimerspec64 * old</code>
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
int do_timerfd_settime(int ufd, int flags, const struct itimerspec64 * new, struct itimerspec64 * old)
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
