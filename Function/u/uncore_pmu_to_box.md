# Function: <code>uncore_pmu_to_box</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578932640,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:90",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init",
        "arch/x86/events/intel/uncore.c:uncore_event_to_box"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init",
        "arch/x86/events/intel/uncore.c:uncore_event_to_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932640,
      "name": "uncore_pmu_to_box.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071578936880,
      "name": "uncore_pmu_to_box",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578931627,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:101",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578933824,
      "name": "uncore_pmu_to_box",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578931851,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:101",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578934272,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578924966,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:101",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578927280,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578927078,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:101",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578929376,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578928918,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:101",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578932256,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578930710,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:101",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578934064,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936408,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:103",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578939616,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936433,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:103",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942096,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578945985,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:103",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949184,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578947905,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:105",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578950784,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578952801,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:122",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955776,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578963375,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:122",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966272,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973631,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:122",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977024,
      "name": "uncore_pmu_to_box",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991919,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:122",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578995664,
      "name": "uncore_pmu_to_box",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991183,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:137",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578995408,
      "name": "uncore_pmu_to_box",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579016063,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:137",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020336,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936433,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:103",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942096,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578933409,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:103",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578939072,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936369,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:103",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942032,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```

```json
{
  "name": "uncore_pmu_to_box",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578936945,
      "name": "uncore_pmu_to_box",
      "external": true,
      "loc": "arch/x86/events/intel/uncore.c:103",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_pmu_disable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_enable",
        "arch/x86/events/intel/uncore.c:uncore_pmu_event_init"
      ],
      "caller_func": [
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942608,
      "name": "uncore_pmu_to_box",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct intel_uncore_box * uncore_pmu_to_box(struct intel_uncore_pmu * pmu, int cpu)
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
