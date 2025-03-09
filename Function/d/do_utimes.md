# Function: <code>do_utimes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_utimes(int dfd, const char * filename, struct timespec * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208080,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:136",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:SyS_utime",
        "fs/utimes.c:SyS_utimensat",
        "fs/utimes.c:SyS_utimes",
        "fs/compat.c:compat_SyS_utime",
        "fs/compat.c:compat_SyS_utimensat",
        "fs/compat.c:compat_SyS_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208080,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
long int do_utimes(int dfd, const char * filename, struct timespec * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372736,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:137",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:SyS_utimes",
        "fs/utimes.c:SyS_utimensat",
        "fs/utimes.c:SyS_utime",
        "fs/compat.c:compat_SyS_utimes",
        "fs/compat.c:compat_SyS_utimensat",
        "fs/compat.c:compat_SyS_utime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372736,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
long int do_utimes(int dfd, const char * filename, struct timespec * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450480,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:122",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:SyS_utimes",
        "fs/utimes.c:SyS_utimensat",
        "fs/utimes.c:SyS_utime",
        "fs/compat.c:compat_SyS_utimes",
        "fs/compat.c:compat_SyS_utimensat",
        "fs/compat.c:compat_SyS_utime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450480,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
long int do_utimes(int dfd, const char * filename, struct timespec * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504528,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:118",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:compat_SyS_utimes",
        "fs/utimes.c:compat_SyS_utimensat",
        "fs/utimes.c:compat_SyS_utime",
        "fs/utimes.c:SyS_utimes",
        "fs/utimes.c:SyS_utimensat",
        "fs/utimes.c:SyS_utime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504528,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
long int do_utimes(int dfd, const char * filename, struct timespec * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581646640,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:119",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:compat_SyS_utimes",
        "fs/utimes.c:compat_SyS_utimensat",
        "fs/utimes.c:compat_SyS_utime",
        "fs/utimes.c:SyS_utimes",
        "fs/utimes.c:SyS_utimensat",
        "fs/utimes.c:SyS_utime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646640,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805584,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:119",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__x32_compat_sys_utimensat",
        "fs/utimes.c:__ia32_compat_sys_utimensat",
        "fs/utimes.c:__x32_compat_sys_utime",
        "fs/utimes.c:__ia32_compat_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805584,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581892592,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:90",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__x32_compat_sys_utimensat",
        "fs/utimes.c:__ia32_compat_sys_utimensat",
        "fs/utimes.c:__x32_compat_sys_utime",
        "fs/utimes.c:__ia32_compat_sys_utime",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892592,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 365
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017792,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:90",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017792,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095712,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095712,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582333184,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333184,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384688,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:138",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384688,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411984,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:139",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411984,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582734368,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:139",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734368,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279952,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:139",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279952,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583862800,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:139",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862800,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584084560,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:140",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584084560,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584300672,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:140",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584300672,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493631776,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__arm64_sys_utimensat_time32",
        "fs/utimes.c:__arm64_sys_utime32",
        "fs/utimes.c:__arm64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493631776,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227172016,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__se_sys_utimensat_time32",
        "fs/utimes.c:__se_sys_utime32",
        "fs/utimes.c:__se_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227172016,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287222944,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__se_sys_utimensat_time32",
        "fs/utimes.c:__se_sys_utime32",
        "fs/utimes.c:__se_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__se_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287222944,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273271598,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:__se_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273271598,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064448,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064448,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002000,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002000,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582055728,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055728,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
long int do_utimes(int dfd, const char * filename, struct timespec64 * times, int flags)
```

```json
{
  "name": "do_utimes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127408,
      "name": "do_utimes",
      "external": true,
      "loc": "fs/utimes.c:88",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_utime",
        "fs/utimes.c:do_compat_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat_time32",
        "fs/utimes.c:__x64_sys_utimensat_time32",
        "fs/utimes.c:__ia32_sys_utime32",
        "fs/utimes.c:__x64_sys_utime32",
        "fs/utimes.c:__ia32_sys_utime",
        "fs/utimes.c:__x64_sys_utime",
        "fs/utimes.c:do_futimesat",
        "fs/utimes.c:__ia32_sys_utimensat",
        "fs/utimes.c:__x64_sys_utimensat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127408,
      "name": "do_utimes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
<code>struct timespec * times</code> ➡️ <code>struct timespec64 * times</code>
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
