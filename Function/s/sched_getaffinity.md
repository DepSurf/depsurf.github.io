# Function: <code>sched_getaffinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558000,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4523",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558000,
      "name": "sched_getaffinity",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568768,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4773",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568768,
      "name": "sched_getaffinity",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593872,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4810",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593872,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578080,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4707",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578080,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607776,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4751",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getaffinity",
        "kernel/compat.c:compat_SyS_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607776,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637984,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4886",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637984,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675664,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:4871",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675664,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707600,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5324",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707600,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579749696,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749696,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785504,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5748",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785504,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776320,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:6572",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776320,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579784912,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:6873",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784912,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879344,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8066",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x64_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879344,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995616,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8174",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995616,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157408,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8358",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157408,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580206240,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8467",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580206240,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580254560,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:8478",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580254560,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490928136,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__arm64_sys_sched_getaffinity",
        "kernel/compat.c:__arm64_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490928136,
      "name": "sched_getaffinity",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224947728,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224947728,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283781424,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__do_sys_sched_getaffinity",
        "kernel/compat.c:__do_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283781424,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271564702,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271564702,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725648,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725648,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654208,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654208,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712400,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712400,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
long int sched_getaffinity(pid_t pid, struct cpumask * mask)
```

```json
{
  "name": "sched_getaffinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757360,
      "name": "sched_getaffinity",
      "external": true,
      "loc": "kernel/sched/core.c:5515",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_getaffinity",
        "kernel/sched/core.c:__x64_sys_sched_getaffinity",
        "kernel/compat.c:__x32_compat_sys_sched_getaffinity",
        "kernel/compat.c:__ia32_compat_sys_sched_getaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757360,
      "name": "sched_getaffinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
