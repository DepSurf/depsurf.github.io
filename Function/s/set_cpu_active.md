# Function: <code>set_cpu_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_cpu_active(unsigned int cpu, bool active)
```

```json
{
  "name": "set_cpu_active",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377568,
      "name": "set_cpu_active",
      "external": true,
      "loc": "kernel/cpu.c:808",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/sched/core.c:sched_cpu_inactive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377568,
      "name": "set_cpu_active",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595247105,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579576761,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:753",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595491249,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:758",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602857,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:758",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596412341,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:801",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581234,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:801",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602737072,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:805",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610578,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:805",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602909537,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:807",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579640498,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:807",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604707152,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:819",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678149,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:819",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604807492,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:818",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710933,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:818",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604841792,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753285,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609176413,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788037,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:846",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612241847,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:852",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779284,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:852",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614382347,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:823",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787436,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:823",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615315176,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:823",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882194,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:823",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617096972,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:849",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999392,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:849",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627757645,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:958",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580161520,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:958",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619518221,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:1010",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580209808,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:1010",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621815229,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:1030",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258128,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:1030",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510874212,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490931124,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243360872,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224949880,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302504020,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283786060,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270616532,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271566730,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604747059,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729205,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604714676,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657813,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604824626,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579714853,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
  "name": "set_cpu_active",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604845949,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760949,
      "name": "set_cpu_active",
      "external": false,
      "loc": "include/linux/cpumask.h:841",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
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
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void set_cpu_active(unsigned int cpu, bool active)
```
</details>
</li>
</ul>
