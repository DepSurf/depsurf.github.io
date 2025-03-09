# Function: <code>housekeeping_enabled</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851648,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851648,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900144,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900144,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943296,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:hk_should_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943296,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931552,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:hk_should_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931552,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939392,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939392,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580064416,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064416,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool housekeeping_enabled(enum hk_type type)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:33",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593879824,
      "name": "housekeeping_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580140592,
      "name": "housekeeping_enabled",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool housekeeping_enabled(enum hk_type type)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:33",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595981616,
      "name": "housekeeping_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580315696,
      "name": "housekeeping_enabled",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool housekeeping_enabled(enum hk_type type)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:33",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596499798,
      "name": "housekeeping_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580382464,
      "name": "housekeeping_enabled",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool housekeeping_enabled(enum hk_type type)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:33",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_do_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597397278,
      "name": "housekeeping_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580439200,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491099280,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491099280,
      "name": "housekeeping_enabled",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225102580,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225102580,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283989440,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283989440,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271681404,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271681404,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872256,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872256,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807264,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807264,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860416,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860416,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
```

```json
{
  "name": "housekeeping_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905792,
      "name": "housekeeping_enabled",
      "external": true,
      "loc": "kernel/sched/isolation.c:17",
      "file": "kernel/sched/isolation.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905792,
      "name": "housekeeping_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool housekeeping_enabled(enum hk_flags flags)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
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
