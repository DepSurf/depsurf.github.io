# Function: <code>security_settime64</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int security_settime64(const struct timespec * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582459264,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:212",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:SyS_stime",
        "kernel/compat.c:compat_SyS_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582459264,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_settime64(const struct timespec * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551728,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:212",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:SyS_stime",
        "kernel/compat.c:compat_SyS_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551728,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_settime64(const struct timespec * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638624,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:783",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_stime",
        "kernel/time/time.c:SyS_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638624,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_settime64(const struct timespec * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792656,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:733",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:compat_SyS_stime",
        "kernel/time/time.c:SyS_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792656,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990912,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:310",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_stime",
        "kernel/time/time.c:__ia32_compat_sys_stime",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990912,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583102496,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__x32_compat_sys_stime",
        "kernel/time/time.c:__ia32_compat_sys_stime",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102496,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583288032,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:791",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288032,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393248,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393248,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732640,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:968",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732640,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583852960,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:970",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852960,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877776,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:994",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877776,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242704,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:994",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242704,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849632,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:993",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849632,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585552224,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:991",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585552224,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585783008,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:1138",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585783008,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586031120,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:1181",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:do_sys_settimeofday64",
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586031120,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495144576,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495144576,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228532300,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228532300,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289064416,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__se_sys_stime32",
        "kernel/time/time.c:__se_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289064416,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274393460,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274393460,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361984,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361984,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299088,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299088,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583345760,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345760,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec64 * ts, const struct timezone * tz)
```

```json
{
  "name": "security_settime64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440944,
      "name": "security_settime64",
      "external": true,
      "loc": "security/security.c:825",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/time.c:__ia32_sys_stime32",
        "kernel/time/time.c:__x64_sys_stime32",
        "kernel/time/time.c:__ia32_sys_stime",
        "kernel/time/time.c:__x64_sys_stime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440944,
      "name": "security_settime64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_settime64(const struct timespec * ts, const struct timezone * tz)
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
<code>const struct timespec * ts</code> ➡️ <code>const struct timespec64 * ts</code>
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
