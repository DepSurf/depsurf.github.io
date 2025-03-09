# Function: <code>release_posix_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579832464,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:570",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_create",
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:exit_itimers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579832464,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861152,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:570",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:SyS_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861152,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916848,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:570",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:SyS_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916848,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579925536,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:473",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925536,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970976,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:479",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970976,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018832,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:488",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018832,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065888,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065888,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109200,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109200,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158368,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158368,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220256,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:478",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220256,
      "name": "release_posix_timer",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204512,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:478",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204512,
      "name": "release_posix_timer",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209808,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:478",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209808,
      "name": "release_posix_timer",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357520,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:478",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357520,
      "name": "release_posix_timer",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572672,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:478",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572672,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833504,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:478",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833504,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491382776,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__arm64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491382776,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225379708,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__se_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225379708,
      "name": "release_posix_timer",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284321040,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__se_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284321040,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271867988,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__se_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271867988,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127568,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127568,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072864,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072864,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118640,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118640,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```

```json
{
  "name": "release_posix_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170496,
      "name": "release_posix_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:452",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:exit_itimers",
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170496,
      "name": "release_posix_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void release_posix_timer(struct k_itimer * tmr, int it_id_set)
```
</details>
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
