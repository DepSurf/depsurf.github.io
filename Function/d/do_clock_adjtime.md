# Function: <code>do_clock_adjtime</code>

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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117408,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1043",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117408,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166736,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166736,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580230134,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1100",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230832,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580214390,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1100",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215088,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580217192,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1100",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220368,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580365048,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1100",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580368304,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580583573,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1109",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584464,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580845125,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1109",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846112,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580928565,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1150",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929584,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581019173,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1150",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020192,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491387712,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491387712,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225383884,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225383884,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284328992,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284328992,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271870868,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271870868,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135936,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135936,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081216,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081216,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127008,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127008,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
```

```json
{
  "name": "do_clock_adjtime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178880,
      "name": "do_clock_adjtime",
      "external": true,
      "loc": "kernel/time/posix-timers.c:1078",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime32",
        "kernel/time/posix-timers.c:__do_sys_clock_adjtime"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178880,
      "name": "do_clock_adjtime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int do_clock_adjtime(const clockid_t which_clock, struct __kernel_timex * ktx)
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
