# Function: <code>do_coredump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void do_coredump(const siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397008,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:506",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397008,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3722
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
void do_coredump(const siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575152,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:533",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575152,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3770
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
void do_coredump(const siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581660032,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:536",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581660032,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3811
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
void do_coredump(const siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714368,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:538",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714368,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3877
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
void do_coredump(const siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860016,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:539",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860016,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3844
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:539",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044613,
      "name": "do_coredump.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582040800,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3813
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:539",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132881,
      "name": "do_coredump.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582128960,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3921
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295184,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582292320,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394160,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582391296,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:567",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680292,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071582678672,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:577",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591344801,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071582748432,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1675
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:577",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591287555,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582776944,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:577",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592244673,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446744071583104160,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:511",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594023911,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071583585840,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2622
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
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189600,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:517",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189600,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2889
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
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417184,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:519",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417184,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2850
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
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584638000,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:519",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638000,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2851
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
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493990664,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493990664,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2828
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
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227455344,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227455344,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3060
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
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287637120,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287637120,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3368
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
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273507724,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273507724,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2466
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362896,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582360032,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300596,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582297744,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2852
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353376,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582350512,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2864
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void do_coredump(const kernel_siginfo_t * siginfo)
```

```json
{
  "name": "do_coredump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_coredump",
      "external": true,
      "loc": "fs/coredump.c:565",
      "file": "fs/coredump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:get_signal",
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433006,
      "name": "do_coredump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582430096,
      "name": "do_coredump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2910
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
<code>const siginfo_t * siginfo</code> ➡️ <code>const kernel_siginfo_t * siginfo</code>
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
