# Function: <code>__lock_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579830720,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:693",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:do_schedule_next_timer",
        "kernel/time/posix-timers.c:SyS_timer_gettime",
        "kernel/time/posix-timers.c:SyS_timer_getoverrun",
        "kernel/time/posix-timers.c:SyS_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830720,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859424,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:693",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:SyS_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_getoverrun",
        "kernel/time/posix-timers.c:SyS_timer_gettime",
        "kernel/time/posix-timers.c:do_schedule_next_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859424,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915136,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:693",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:SyS_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_getoverrun",
        "kernel/time/posix-timers.c:SyS_timer_gettime",
        "kernel/time/posix-timers.c:do_schedule_next_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915136,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923264,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:609",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:do_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923264,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579968624,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:615",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:SyS_timer_delete",
        "kernel/time/posix-timers.c:do_timer_settime",
        "kernel/time/posix-timers.c:SyS_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968624,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016224,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:624",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016224,
      "name": "__lock_timer",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063232,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063232,
      "name": "__lock_timer",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106896,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106896,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155952,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155952,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220576,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:614",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220576,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204832,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:614",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204832,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580210128,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:614",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210128,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580355472,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:614",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580355472,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580570048,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:614",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_settime",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580570048,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830496,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:614",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_settime",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830496,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914048,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:560",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_settime",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914048,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581004656,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:560",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:do_timer_settime",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581004656,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491383032,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__arm64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__arm64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491383032,
      "name": "__lock_timer",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225376560,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__se_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225376560,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284316880,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__se_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284316880,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271865822,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__se_sys_timer_delete",
        "kernel/time/posix-timers.c:__se_sys_timer_settime",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__se_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__se_sys_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271865822,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580125152,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125152,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070448,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070448,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580116224,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580116224,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct k_itimer * __lock_timer(timer_t timer_id, long unsigned int * flags)
```

```json
{
  "name": "__lock_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168176,
      "name": "__lock_timer",
      "external": false,
      "loc": "kernel/time/posix-timers.c:588",
      "file": "kernel/time/posix-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-timers.c:__ia32_sys_timer_delete",
        "kernel/time/posix-timers.c:__x64_sys_timer_delete",
        "kernel/time/posix-timers.c:timer_wait_running",
        "kernel/time/posix-timers.c:__ia32_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:__x64_sys_timer_getoverrun",
        "kernel/time/posix-timers.c:do_timer_gettime",
        "kernel/time/posix-timers.c:posixtimer_rearm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168176,
      "name": "__lock_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
