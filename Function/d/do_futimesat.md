# Function: <code>do_futimesat</code>

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
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806304,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:187",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806304,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893152,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:165",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893152,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018336,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:165",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018336,
      "name": "do_futimesat",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582096256,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:163",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582096256,
      "name": "do_futimesat",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582333712,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:165",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333712,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582385152,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:172",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385152,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412464,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:173",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412464,
      "name": "do_futimesat",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582734848,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:173",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734848,
      "name": "do_futimesat",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280544,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:173",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280544,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863424,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:173",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863424,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584085184,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:174",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085184,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
long int do_futimesat(int dfd, const char * filename, struct __kernel_old_timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584301280,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:174",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301280,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287223776,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:163",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__se_sys_utimes",
        "fs/utimes.c:__se_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287223776,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064992,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:163",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064992,
      "name": "do_futimesat",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582002544,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:163",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582002544,
      "name": "do_futimesat",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056272,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:163",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056272,
      "name": "do_futimesat",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```

```json
{
  "name": "do_futimesat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127952,
      "name": "do_futimesat",
      "external": false,
      "loc": "fs/utimes.c:163",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:__ia32_sys_utimes",
        "fs/utimes.c:__x64_sys_utimes",
        "fs/utimes.c:__ia32_sys_futimesat",
        "fs/utimes.c:__x64_sys_futimesat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127952,
      "name": "do_futimesat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timeval * utimes</code> ➡️ <code>struct __kernel_old_timeval * utimes</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_futimesat(int dfd, const char * filename, struct timeval * utimes)
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
