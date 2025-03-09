# Function: <code>kthread_bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502352,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:378",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502352,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516416,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:378",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516416,
      "name": "kthread_bind",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539286,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:408",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538544,
      "name": "kthread_bind",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526151,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:412",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525472,
      "name": "kthread_bind",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579552311,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:419",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551488,
      "name": "kthread_bind",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579579527,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:433",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577760,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579616711,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:433",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615792,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641054,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640848,
      "name": "kthread_bind",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579667486,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667280,
      "name": "kthread_bind",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579700938,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:478",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697744,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579679098,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:480",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675712,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579685370,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:507",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683104,
      "name": "kthread_bind",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579763676,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:507",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760816,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579869445,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:566",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867968,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012165,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:566",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010688,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580065701,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:567",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064336,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108354,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:566",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106896,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490844824,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490844568,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224875520,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224873344,
      "name": "kthread_bind",
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283681476,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283681216,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271513682,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271512196,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579643806,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643600,
      "name": "kthread_bind",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579572190,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571984,
      "name": "kthread_bind",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641070,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640864,
      "name": "kthread_bind",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void kthread_bind(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "kthread_bind",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675310,
      "name": "kthread_bind",
      "external": true,
      "loc": "kernel/kthread.c:442",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_create_worker",
        "kernel/kthread.c:kthread_create_on_cpu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675104,
      "name": "kthread_bind",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
