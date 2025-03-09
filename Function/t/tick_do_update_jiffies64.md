# Function: <code>tick_do_update_jiffies64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886432,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:52",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_do_timer",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_irq_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886432,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916016,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:52",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916016,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579949016,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:52",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946656,
      "name": "tick_do_update_jiffies64.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956936,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:56",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954560,
      "name": "tick_do_update_jiffies64.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002728,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001392,
      "name": "tick_do_update_jiffies64.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055336,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052912,
      "name": "tick_do_update_jiffies64.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580102168,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099744,
      "name": "tick_do_update_jiffies64.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580146104,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143632,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071580146907,
      "name": "tick_do_update_jiffies64.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580194136,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191664,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580257378,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257008,
      "name": "tick_do_update_jiffies64.part.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580240640,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240640,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071580240800,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580246256,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580246256,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580396960,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_sched_timer",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_handler",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396960,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580613904,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_do_timer",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580613904,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580878672,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_do_timer",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878672,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580963184,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_do_timer",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963184,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void tick_do_update_jiffies64(ktime_t now)
```

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581055040,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:57",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_nohz_update_jiffies",
        "kernel/time/tick-sched.c:tick_sched_do_timer",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055040,
      "name": "tick_do_update_jiffies64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491424512,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491420704,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225418432,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225413944,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284372596,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284368480,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271891696,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271888718,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580162936,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160464,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580110554,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106816,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580154408,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580151936,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_do_update_jiffies64",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580206424,
      "name": "tick_do_update_jiffies64",
      "external": false,
      "loc": "kernel/time/tick-sched.c:54",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick",
        "kernel/time/tick-sched.c:tick_sched_do_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580203760,
      "name": "tick_do_update_jiffies64.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void tick_do_update_jiffies64(ktime_t now)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void tick_do_update_jiffies64(ktime_t now)
```
</details>
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
