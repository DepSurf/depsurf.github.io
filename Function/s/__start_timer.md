# Function: <code>__start_timer</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129904,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:1376",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129904,
      "name": "__start_timer",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579130224,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:1357",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130224,
      "name": "__start_timer",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147888,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:1367",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147888,
      "name": "__start_timer",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579157664,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:1345",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_start_timer",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157664,
      "name": "__start_timer",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147152,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1361",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147152,
      "name": "__start_timer",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159840,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1394",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159840,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579162304,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1394",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579162304,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181808,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1397",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181808,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579178192,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1472",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178192,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187328,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1484",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187328,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222176,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1545",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222176,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267408,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1608",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267408,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579330224,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1608",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330224,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579339056,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1621",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339056,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368928,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1645",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368928,
      "name": "__start_timer",
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
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579162656,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1394",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579162656,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090944,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1394",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090944,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579162224,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1394",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579162224,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void __start_timer(struct timer_list * t, long unsigned int interval)
```

```json
{
  "name": "__start_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579167408,
      "name": "__start_timer",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1394",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start_timer",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_kick",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167408,
      "name": "__start_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __start_timer(struct timer_list * t, long unsigned int interval)
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
