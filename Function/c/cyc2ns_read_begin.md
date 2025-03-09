# Function: <code>cyc2ns_read_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cyc2ns_data * cyc2ns_read_begin()
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073808,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:82",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073808,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cyc2ns_data * cyc2ns_read_begin()
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070240,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:83",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070240,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cyc2ns_data * cyc2ns_read_begin()
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579069520,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:84",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069520,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061795,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061696,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579070851,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070752,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579074943,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:63",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073424,
      "name": "cyc2ns_read_begin.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071579074880,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604612525,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:61",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579080800,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579090512,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090432,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579092496,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:tunables_write",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092416,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579104256,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:69",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:native_sched_clock",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/platform/uv/tlb_uv.c:tunables_write",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579104176,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579104448,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:69",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:native_sched_clock",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579104368,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110960,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:70",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:native_sched_clock",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579110880,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579135825,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:70",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:native_sched_clock",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135696,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579172081,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:70",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:native_sched_clock",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171920,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579226225,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:70",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:native_sched_clock",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226032,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231520,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:87",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231520,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579260384,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:87",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579260384,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579092848,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092768,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579024992,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579024912,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579092432,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092352,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```

```json
{
  "name": "cyc2ns_read_begin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096640,
      "name": "cyc2ns_read_begin",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:62",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:native_sched_clock_from_tsc",
        "arch/x86/kernel/tsc.c:native_sched_clock",
        "arch/x86/kernel/tsc.c:__set_cyc2ns_scale"
      ],
      "caller_func": [
        "arch/x86/events/core.c:arch_perf_update_userpage",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:init_per_cpu",
        "arch/x86/platform/uv/tlb_uv.c:tunables_write",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:ptc_seq_show",
        "arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion",
        "arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096528,
      "name": "cyc2ns_read_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cyc2ns_data * data</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct cyc2ns_data *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
void cyc2ns_read_begin(struct cyc2ns_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cyc2ns_read_begin(struct cyc2ns_data * data)
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
