# Function: <code>__do_sys_clock_adjtime32</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117744,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1125",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117744,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167072,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167072,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230048,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1182",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230048,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580214304,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1182",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214304,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217104,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1182",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217104,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580364960,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1182",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364960,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580583456,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1191",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580583456,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845008,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1191",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845008,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928448,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1305",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928448,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581019056,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1305",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581019056,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491388368,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491388368,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225384316,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225384316,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284329424,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284329424,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136272,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136272,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081552,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081552,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127344,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127344,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```

```json
{
  "name": "__do_sys_clock_adjtime32",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179216,
      "name": "__do_sys_clock_adjtime32",
      "external": false,
      "loc": "kernel/time/posix-timers.c:1160",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__x64_sys_clock_adjtime32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179216,
      "name": "__do_sys_clock_adjtime32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
```
</details>
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
long int __do_sys_clock_adjtime32(clockid_t which_clock, struct old_timex32 * utp)
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
