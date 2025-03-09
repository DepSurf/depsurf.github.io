# Function: <code>__tasklet_schedule_common</code>

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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579454496,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:470",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454496,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488304,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488304,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506448,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506448,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532496,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532496,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563141,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:498",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579544613,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:502",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579549621,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:719",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
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
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579622453,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:718",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716720,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:732",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716720,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843696,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:732",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843696,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893920,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:714",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893920,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932608,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:714",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932608,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490677648,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490677648,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224748500,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224748500,
      "name": "__tasklet_schedule_common",
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283501376,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283501376,
      "name": "__tasklet_schedule_common",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271414214,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271414214,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506160,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506160,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434976,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434976,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506080,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506080,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```

```json
{
  "name": "__tasklet_schedule_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538752,
      "name": "__tasklet_schedule_common",
      "external": false,
      "loc": "kernel/softirq.c:471",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__tasklet_hi_schedule",
        "kernel/softirq.c:__tasklet_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538752,
      "name": "__tasklet_schedule_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct * t, struct tasklet_head * headp, unsigned int softirq_nr)
```
</details>
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
