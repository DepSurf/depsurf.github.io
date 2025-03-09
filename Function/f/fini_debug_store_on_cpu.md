# Function: <code>fini_debug_store_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578911296,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:252",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578911296,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578909744,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:261",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909744,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578910112,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:261",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910112,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578903566,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:271",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578903472,
      "name": "fini_debug_store_on_cpu",
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578905532,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578905376,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578907931,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578907744,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578909419,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578909232,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578913803,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578913616,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578915563,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915376,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578921307,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:276",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578921120,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578920187,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:276",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578920000,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578924507,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:341",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578924320,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578929199,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:341",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578928960,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936862,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:390",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936608,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578953457,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:397",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578953200,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578952065,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:445",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578951808,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975457,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:450",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975200,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578915563,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915376,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578910859,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578910672,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578915499,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915312,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```

```json
{
  "name": "fini_debug_store_on_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578916027,
      "name": "fini_debug_store_on_cpu",
      "external": true,
      "loc": "arch/x86/events/intel/ds.c:275",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:release_ds_buffers",
        "arch/x86/events/intel/ds.c:release_ds_buffers"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578915840,
      "name": "fini_debug_store_on_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void fini_debug_store_on_cpu(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void fini_debug_store_on_cpu(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void fini_debug_store_on_cpu(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fini_debug_store_on_cpu(int cpu)
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
