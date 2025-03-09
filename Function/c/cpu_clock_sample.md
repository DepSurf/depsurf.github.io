# Function: <code>cpu_clock_sample</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, long long unsigned int * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837552,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:180",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837552,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, long long unsigned int * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866448,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:180",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866448,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, long long unsigned int * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579922144,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:179",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_schedule",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922144,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931504,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:160",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931504,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977024,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:161",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977024,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028144,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:162",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028144,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075024,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:162",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075024,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int cpu_clock_sample(const clockid_t which_clock, struct task_struct * p, u64 * sample)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118464,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:162",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118464,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580169472,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169472,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580231664,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:187",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231664,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580215872,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:187",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215872,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580221136,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:187",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221136,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580370931,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:187",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580587550,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:194",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580849486,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:194",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580933182,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:194",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581020896,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:194",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020896,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491390736,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491390736,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225388636,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225388636,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284333200,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284333200,
      "name": "cpu_clock_sample",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271873646,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271873646,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580138672,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138672,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580083824,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083824,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580129744,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129744,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```

```json
{
  "name": "cpu_clock_sample",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580181696,
      "name": "cpu_clock_sample",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:197",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_rearm",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_get",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_set",
        "kernel/time/posix-cpu-timers.c:posix_cpu_clock_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181696,
      "name": "cpu_clock_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long long unsigned int * sample</code> ➡️ <code>u64 * sample</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const clockid_t clkid</code>
</li>
<li>
<b>Param removed. </b>
<code>const clockid_t which_clock</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 * sample</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
u64 cpu_clock_sample(const clockid_t clkid, struct task_struct * p)
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
