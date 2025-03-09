# Function: <code>intel_pmu_lbr_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578916272,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:202",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578916272,
      "name": "intel_pmu_lbr_reset.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071578916464,
      "name": "intel_pmu_lbr_reset",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578915618,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:213",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914544,
      "name": "intel_pmu_lbr_reset.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071578914768,
      "name": "intel_pmu_lbr_reset",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578916001,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:213",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914896,
      "name": "intel_pmu_lbr_reset.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071578915120,
      "name": "intel_pmu_lbr_reset",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578909425,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:213",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578908416,
      "name": "intel_pmu_lbr_reset.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071578908624,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578911377,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910368,
      "name": "intel_pmu_lbr_reset.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071578910576,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578914033,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578912800,
      "name": "intel_pmu_lbr_reset.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071578913008,
      "name": "intel_pmu_lbr_reset",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578914304,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578914304,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578919392,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578919392,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578921360,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578921360,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578927552,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578927552,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578929576,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:271",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578928032,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578933982,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:271",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932480,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578939630,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:271",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578938144,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578946752,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:249",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578946752,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578962816,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:189",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962816,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578961984,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:189",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578961984,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578986448,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:189",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_del",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986448,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578921360,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578921360,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578917056,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578917056,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578921296,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578921296,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void intel_pmu_lbr_reset()
```

```json
{
  "name": "intel_pmu_lbr_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578921840,
      "name": "intel_pmu_lbr_reset",
      "external": true,
      "loc": "arch/x86/events/intel/lbr.c:217",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_add",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578921840,
      "name": "intel_pmu_lbr_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_pmu_lbr_reset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_pmu_lbr_reset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_pmu_lbr_reset()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_pmu_lbr_reset()
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
