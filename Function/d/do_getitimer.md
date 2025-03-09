# Function: <code>do_getitimer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829216,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:79",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:SyS_getitimer",
        "kernel/compat.c:compat_SyS_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829216,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857936,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:79",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:SyS_getitimer",
        "kernel/compat.c:compat_SyS_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857936,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933392,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:79",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:SyS_getitimer",
        "kernel/compat.c:compat_SyS_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933392,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941040,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:82",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_getitimer",
        "kernel/time/itimer.c:SyS_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941040,
      "name": "do_getitimer",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986688,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:83",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:compat_SyS_getitimer",
        "kernel/time/itimer.c:SyS_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986688,
      "name": "do_getitimer",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038048,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:83",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038048,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084848,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:81",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084848,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128512,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:81",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128512,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176768,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176768,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580242784,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242784,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227024,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227024,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232256,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232256,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381264,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x64_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381264,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580595360,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580595360,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858080,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858080,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941872,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941872,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int do_getitimer(int which, struct itimerspec64 * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033168,
      "name": "do_getitimer",
      "external": false,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033168,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491399712,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__arm64_compat_sys_getitimer",
        "kernel/time/itimer.c:__arm64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491399712,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225397124,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225397124,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284343440,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_compat_sys_getitimer",
        "kernel/time/itimer.c:__se_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284343440,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271879798,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__se_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271879798,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145968,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145968,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091504,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091504,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137040,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137040,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int do_getitimer(int which, struct itimerval * value)
```

```json
{
  "name": "do_getitimer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188960,
      "name": "do_getitimer",
      "external": true,
      "loc": "kernel/time/itimer.c:76",
      "file": "kernel/time/itimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/itimer.c:__x32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_compat_sys_getitimer",
        "kernel/time/itimer.c:__ia32_sys_getitimer",
        "kernel/time/itimer.c:__x64_sys_getitimer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188960,
      "name": "do_getitimer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct itimerval * value</code> ➡️ <code>struct itimerspec64 * value</code>
</li>
</ul>
</details>
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
