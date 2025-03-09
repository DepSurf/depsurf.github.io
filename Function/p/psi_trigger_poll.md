# Function: <code>psi_trigger_poll</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858304,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1160",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858304,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579906848,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906848,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579948597,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1210",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_fop_poll"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948080,
      "name": "psi_trigger_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071579950928,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579937061,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1222",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_fop_poll"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935856,
      "name": "psi_trigger_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071579939488,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579947024,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1254",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947024,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073776,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1222",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073776,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208208,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1225",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208208,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400720,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1401",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400720,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469488,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1465",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469488,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529312,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1457",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529312,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491107328,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491107328,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225106960,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_fop_poll"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225106728,
      "name": "psi_trigger_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 3225111684,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283999216,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283999216,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271685804,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_fop_poll"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271685616,
      "name": "psi_trigger_poll.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446743936271688600,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878960,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878960,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579813952,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813952,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579867120,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867120,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```

```json
{
  "name": "psi_trigger_poll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579912496,
      "name": "psi_trigger_poll",
      "external": true,
      "loc": "kernel/sched/psi.c:1161",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_poll",
        "kernel/cgroup/cgroup.c:cgroup_pressure_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912496,
      "name": "psi_trigger_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
__poll_t psi_trigger_poll(void * * trigger_ptr, struct file * file, poll_table * wait)
```
</details>
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
