# Function: <code>do_sys_settimeofday64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579836336,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:163",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:SyS_settimeofday",
        "kernel/time/time.c:SyS_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set",
        "kernel/time/posix-timers.c:posix_clock_realtime_set",
        "kernel/compat.c:compat_SyS_settimeofday",
        "kernel/compat.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836336,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579865392,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:163",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:SyS_settimeofday",
        "kernel/time/time.c:SyS_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set",
        "kernel/time/posix-timers.c:posix_clock_realtime_set",
        "kernel/compat.c:compat_SyS_settimeofday",
        "kernel/compat.c:compat_SyS_settimeofday"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865392,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579874528,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:205",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_settimeofday",
        "kernel/time/time.c:SyS_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874528,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917952,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:171",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_settimeofday",
        "kernel/time/time.c:SyS_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917952,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579964048,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:172",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964048,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580010912,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010912,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054224,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054224,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103280,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103280,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165520,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165520,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149664,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149664,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580154320,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154320,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580298848,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x64_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580298848,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507824,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507824,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761664,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761664,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844336,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844336,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933728,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933728,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491317808,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__arm64_compat_sys_settimeofday",
        "kernel/time/time.c:__arm64_compat_sys_settimeofday",
        "kernel/time/time.c:__arm64_compat_sys_settimeofday",
        "kernel/time/time.c:__arm64_sys_settimeofday",
        "kernel/time/time.c:__arm64_sys_settimeofday",
        "kernel/time/time.c:__arm64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491317808,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225310908,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225310908,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284241408,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_compat_sys_settimeofday",
        "kernel/time/time.c:__se_compat_sys_settimeofday",
        "kernel/time/time.c:__se_compat_sys_settimeofday",
        "kernel/time/time.c:__se_sys_settimeofday",
        "kernel/time/time.c:__se_sys_settimeofday",
        "kernel/time/time.c:__se_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284241408,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271821452,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_sys_settimeofday",
        "kernel/time/time.c:__se_sys_settimeofday",
        "kernel/time/time.c:__se_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271821452,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580072480,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072480,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580017296,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017296,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580063552,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063552,
      "name": "do_sys_settimeofday64",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int do_sys_settimeofday64(const struct timespec64 * tv, const struct timezone * tz)
```

```json
{
  "name": "do_sys_settimeofday64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580114320,
      "name": "do_sys_settimeofday64",
      "external": true,
      "loc": "kernel/time/time.c:169",
      "file": "kernel/time/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__x32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_compat_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__ia32_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/time.c:__x64_sys_settimeofday",
        "kernel/time/posix-timers.c:posix_clock_realtime_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114320,
      "name": "do_sys_settimeofday64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int do_sys_settimeofday64(const struct timespec * tv, const struct timezone * tz)
```
</details>
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
<code>const struct timespec * tv</code> ➡️ <code>const struct timespec64 * tv</code>
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
