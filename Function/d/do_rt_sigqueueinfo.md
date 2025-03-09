# Function: <code>do_rt_sigqueueinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433616,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:2938",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:SYSC_rt_sigqueueinfo",
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433616,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446032,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:2938",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446032,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579466400,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:2951",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466400,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579454944,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3006",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454944,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483264,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3027",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:C_SYSC_rt_sigqueueinfo",
        "kernel/signal.c:SYSC_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483264,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int do_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499824,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3260",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__do_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__do_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499824,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533456,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3588",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533456,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556176,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3836",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556176,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582320,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582320,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619568,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3862",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619568,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599968,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3883",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599968,
      "name": "do_rt_sigqueueinfo",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605472,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3905",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605472,
      "name": "do_rt_sigqueueinfo",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680752,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3993",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x64_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680752,
      "name": "do_rt_sigqueueinfo",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579775216,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3976",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579775216,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907600,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3978",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907600,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957328,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4002",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957328,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579996608,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4013",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579996608,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490745984,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__arm64_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__arm64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490745984,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224803864,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283570608,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__se_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283570608,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271456586,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558624,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558624,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487280,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487280,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579555904,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555904,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
```

```json
{
  "name": "do_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589232,
      "name": "do_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3844",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo",
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589232,
      "name": "do_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>siginfo_t * info</code> ➡️ <code>kernel_siginfo_t * info</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
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
int do_rt_sigqueueinfo(pid_t pid, int sig, kernel_siginfo_t * info)
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
