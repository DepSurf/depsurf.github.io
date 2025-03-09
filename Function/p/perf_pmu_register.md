# Function: <code>perf_pmu_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411152,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:7624",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/rapl.c:rapl_pmu_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411152,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 759
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580478096,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:8640",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478096,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537840,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:8829",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537840,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565712,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:9040",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565712,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 955
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580650800,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:9056",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580650800,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779648,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:9578",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779648,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 975
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845504,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:9621",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845504,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1006
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940416,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:9930",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940416,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1029
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994016,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994016,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1029
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160288,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10594",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160288,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1117
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581195792,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10876",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581195792,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1117
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581208656,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:11006",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208656,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1117
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448816,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:11118",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448816,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1165
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792208,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:11054",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792208,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582225472,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:11394",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225472,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 907
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:11437",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545372,
      "name": "perf_pmu_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582420800,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 873
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:11521",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/events/amd/iommu.c:init_one_iommu",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449067,
      "name": "perf_pmu_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582589600,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 873
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492332248,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_tp_register",
        "kernel/events/core.c:perf_tp_register",
        "kernel/events/core.c:perf_tp_register",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm_pmu.c:armpmu_register",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe",
        "drivers/perf/xgene_pmu.c:xgene_pmu_dev_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492332248,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226222824,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint",
        "drivers/perf/arm-cci.c:cci_pmu_probe",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm_pmu.c:armpmu_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226222824,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285596912,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/core-book3s.c:register_power_pmu",
        "arch/powerpc/perf/imc-pmu.c:init_imc_pmu",
        "arch/powerpc/perf/hv-24x7.c:hv_24x7_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285596912,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1400
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272462510,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/perf_event.c:init_hw_perf_events",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272462510,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962816,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962816,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1029
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908944,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908944,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1029
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954064,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954064,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1029
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
int perf_pmu_register(struct pmu * pmu, const char * name, int type)
```

```json
{
  "name": "perf_pmu_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581018528,
      "name": "perf_pmu_register",
      "external": true,
      "loc": "kernel/events/core.c:10046",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:perf_ibs_pmu_init",
        "arch/x86/events/amd/iommu.c:amd_iommu_pc_init",
        "arch/x86/events/msr.c:msr_init",
        "arch/x86/events/intel/bts.c:bts_init",
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/uncore.c:uncore_pmu_register",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/core.c:perf_event_init",
        "kernel/events/hw_breakpoint.c:init_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018528,
      "name": "perf_pmu_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1029
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
