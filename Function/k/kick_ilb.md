# Function: <code>kick_ilb</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579651024,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9344",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579651024,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579688864,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9447",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688864,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722656,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9364",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:pick_next_task_fair"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722656,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579765408,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765408,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799440,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:10026",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_newidle_balance",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799440,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790656,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:10140",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_newidle_balance",
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790656,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579855096,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:10179",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balancer_kick"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579961233,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:10421",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balancer_kick"
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
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580076282,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:10523",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balancer_kick"
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
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580247516,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:11051",
      "file": "kernel/sched/fair.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:nohz_balancer_kick"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580235776,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:11351",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580235776,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285072,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:11817",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:nohz_balancer_kick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285072,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490951672,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490951672,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224964992,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224964992,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283804560,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283804560,
      "name": "kick_ilb",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271576712,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271576712,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741264,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741264,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671648,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671648,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725776,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725776,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void kick_ilb(unsigned int flags)
```

```json
{
  "name": "kick_ilb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773312,
      "name": "kick_ilb",
      "external": false,
      "loc": "kernel/sched/fair.c:9348",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:trigger_load_balance",
        "kernel/sched/fair.c:newidle_balance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773312,
      "name": "kick_ilb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void kick_ilb(unsigned int flags)
```
</details>
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
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void kick_ilb(unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void kick_ilb(unsigned int flags)
```
</details>
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
