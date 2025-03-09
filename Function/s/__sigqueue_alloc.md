# Function: <code>__sigqueue_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422064,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:361",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:sigqueue_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422064,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434816,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:361",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434816,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455168,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:361",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455168,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443024,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:367",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443024,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471328,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:369",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471328,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:371",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485648,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071579512420,
      "name": "__sigqueue_alloc.cold.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:402",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519024,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071579548260,
      "name": "__sigqueue_alloc.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538608,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071579569989,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564672,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071579596437,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597008,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
    },
    {
      "addr": 18446744071579629029,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:413",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577184,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071591279164,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:411",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582880,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071591221996,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656816,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071592101331,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753072,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071593868886,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884448,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884448,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933712,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:413",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933712,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973040,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:404",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973040,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490726432,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490726432,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224780032,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224780032,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283547968,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283547968,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271439004,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271439004,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540976,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071579572741,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469728,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071579501349,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538256,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071579570021,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
struct sigqueue * __sigqueue_alloc(int sig, struct task_struct * t, gfp_t flags, int override_rlimit)
```

```json
{
  "name": "__sigqueue_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sigqueue_alloc",
      "external": false,
      "loc": "kernel/signal.c:412",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:sigqueue_alloc",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571552,
      "name": "__sigqueue_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071579603517,
      "name": "__sigqueue_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param added. </b>
<code>const unsigned int sigqueue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t flags</code>
</li>
</ul>
</details>
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
