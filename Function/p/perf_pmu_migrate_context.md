# Function: <code>perf_pmu_migrate_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409536,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:8660",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/cstate.c:cstate_cpu_notifier",
        "arch/x86/events/intel/rapl.c:rapl_cpu_notifier",
        "arch/x86/events/intel/uncore.c:uncore_change_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409536,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483600,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:9844",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483600,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580549152,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:10104",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580549152,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580896,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:10351",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580896,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660624,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:10383",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660624,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791472,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:10913",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791472,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857840,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:10956",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857840,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954496,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11307",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954496,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016848,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016848,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188528,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:12023",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/intel/uncore.c:uncore_change_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188528,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 914
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230160,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:12307",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/intel/uncore.c:uncore_change_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230160,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 914
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256960,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:12497",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare",
        "arch/x86/events/intel/uncore.c:uncore_change_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256960,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504768,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:12618",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504768,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581846848,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:12588",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581846848,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1067
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274880,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:12869",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274880,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582475744,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:12909",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475744,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 661
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582644448,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:13001",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:uncore_change_context",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582644448,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492369848,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu",
        "drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu",
        "drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu",
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu",
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu",
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu",
        "drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492369848,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226254720,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226254720,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285624192,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline",
        "arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285624192,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272478480,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272478480,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985696,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985696,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931904,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931904,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976896,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976896,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void perf_pmu_migrate_context(struct pmu * pmu, int src_cpu, int dst_cpu)
```

```json
{
  "name": "perf_pmu_migrate_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037712,
      "name": "perf_pmu_migrate_context",
      "external": true,
      "loc": "kernel/events/core.c:11420",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/uncore.c:uncore_down_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037712,
      "name": "perf_pmu_migrate_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
