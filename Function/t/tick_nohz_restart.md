# Function: <code>tick_nohz_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887088,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:557",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887088,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916672,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:649",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:__tick_nohz_idle_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916672,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946544,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:647",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946544,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579956617,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:657",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580002409,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053567,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:623",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580100399,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:620",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580144298,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:629",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580192317,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256432,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:658",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256432,
      "name": "tick_nohz_restart",
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580240064,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:706",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240064,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245312,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:707",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245312,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580395984,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:742",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395984,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580615264,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:758",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615264,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580880144,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:758",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580880144,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580964656,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:774",
      "file": "kernel/time/tick-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_nohz_idle_restart_tick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964656,
      "name": "tick_nohz_restart",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581056018,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:775",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491421176,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225414988,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284369668,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271889650,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580161117,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580107485,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:tick_nohz_restart_sched_tick"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580152589,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_nohz_restart",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580204397,
      "name": "tick_nohz_restart",
      "external": false,
      "loc": "kernel/time/tick-sched.c:633",
      "file": "kernel/time/tick-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick"
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void tick_nohz_restart(struct tick_sched * ts, ktime_t now)
```
</details>
</li>
</ul>
