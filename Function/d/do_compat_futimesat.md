# Function: <code>do_compat_futimesat</code>

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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct compat_timeval * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581807008,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:263",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__x32_compat_sys_utimes",
        "fs/utimes.c:__ia32_compat_sys_utimes",
        "fs/utimes.c:__x32_compat_sys_futimesat",
        "fs/utimes.c:__ia32_compat_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581807008,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581894000,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:259",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__x32_compat_sys_utimes",
        "fs/utimes.c:__ia32_compat_sys_utimes",
        "fs/utimes.c:__x32_compat_sys_futimesat",
        "fs/utimes.c:__ia32_compat_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581894000,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019200,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:259",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019200,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582097120,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582097120,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582334528,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:259",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334528,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385968,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:266",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385968,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413328,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:267",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413328,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735712,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:267",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735712,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281648,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:267",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281648,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583864656,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:267",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583864656,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086416,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:268",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086416,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584302512,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:268",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584302512,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493633368,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__arm64_sys_utimes_time32",
        "fs/utimes.c:__arm64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493633368,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227172368,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__se_sys_utimes_time32",
        "fs/utimes.c:__se_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227172368,
      "name": "do_compat_futimesat",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287225248,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__se_sys_utimes_time32",
        "fs/utimes.c:__se_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287225248,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582065856,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065856,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582003408,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003408,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057136,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057136,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
```

```json
{
  "name": "do_compat_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582128816,
      "name": "do_compat_futimesat",
      "external": false,
      "loc": "fs/utimes.c:257",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes_time32",
        "fs/utimes.c:__x64_sys_utimes_time32",
        "fs/utimes.c:__ia32_sys_futimesat_time32",
        "fs/utimes.c:__x64_sys_futimesat_time32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582128816,
      "name": "do_compat_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct compat_timeval * t)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct compat_timeval * t</code> ➡️ <code>struct old_timeval32 * t</code>
</li>
</ul>
</details>
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
long int do_compat_futimesat(unsigned int dfd, const char * filename, struct old_timeval32 * t)
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
