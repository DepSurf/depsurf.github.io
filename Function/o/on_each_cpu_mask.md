# Function: <code>on_each_cpu_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909904,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:622",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_count",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_count",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_destroy",
        "arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond",
        "mm/page_alloc.c:drain_all_pages",
        "drivers/cpuidle/driver.c:cpuidle_register_driver",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "net/core/flow.c:flow_cache_flush",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909904,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939616,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:607",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_destroy",
        "arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond",
        "mm/page_alloc.c:drain_all_pages",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "drivers/cpuidle/driver.c:cpuidle_register_driver",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939616,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970736,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:614",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_event_destroy",
        "arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/events/intel/cqm.c:intel_cqm_xchg_rmid",
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond",
        "mm/page_alloc.c:drain_all_pages",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "drivers/cpuidle/driver.c:cpuidle_register_driver",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970736,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579976128,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:625",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "drivers/cpuidle/driver.c:cpuidle_register_driver",
        "net/core/flow.c:flow_cache_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976128,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022576,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:627",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "drivers/cpuidle/driver.c:cpuidle_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022576,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076640,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:629",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "drivers/cpuidle/driver.c:cpuidle_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076640,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123952,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:627",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "drivers/cpuidle/driver.c:cpuidle_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123952,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580169456,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond_mask",
        "drivers/cpuidle/driver.c:cpuidle_unregister_driver",
        "drivers/cpuidle/driver.c:cpuidle_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169456,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217392,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217392,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285248,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:723",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285248,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268768,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:860",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "kernel/sched/membarrier.c:membarrier_private_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268768,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578869624,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579087216,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273168,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419111,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938585,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586812927,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588814285,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588846328,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "on_each_cpu_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871336,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579110304,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315678,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482611,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi",
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580063560,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371321,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589507325,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589544685,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "on_each_cpu_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578868250,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579141352,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374054,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561513,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580147218,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590991517,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591037423,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "on_each_cpu_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873738,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579185736,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442863,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449526,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668909,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580343584,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592697677,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592748671,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "on_each_cpu_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871594,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579189794,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409697,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429262,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454959,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461686,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682877,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580410598,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593128646,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593183327,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "on_each_cpu_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578893866,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579219026,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438650,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458846,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579484927,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579491750,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717325,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:native_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580466818,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sync_runqueues_membarrier_state",
        "kernel/sched/build_utility.c:membarrier_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593422,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:trace_buffered_event_disable",
        "kernel/trace/trace.c:trace_buffered_event_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593881814,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593937151,
      "name": "on_each_cpu_mask",
      "external": false,
      "loc": "include/linux/smp.h:90",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491456176,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491456176,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225442332,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_tlb.c:flush_tlb_range",
        "arch/arm/kernel/smp_tlb.c:flush_tlb_page",
        "arch/arm/kernel/smp_tlb.c:flush_tlb_mm",
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225442332,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284407056,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_collapsed_pmd",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_range_psize",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlb_flush",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__radix__flush_tlb_range",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_page_psize",
        "arch/powerpc/mm/book3s64/radix_tlb.c:__flush_all_mm",
        "arch/powerpc/mm/book3s64/radix_tlb.c:radix__flush_tlb_mm",
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284407056,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271911972,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271911972,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580186192,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186192,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133664,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133664,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177664,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177664,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```

```json
{
  "name": "on_each_cpu_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229872,
      "name": "on_each_cpu_mask",
      "external": true,
      "loc": "kernel/smp.c:640",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "kernel/smp.c:on_each_cpu_cond_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229872,
      "name": "on_each_cpu_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void on_each_cpu_mask(const struct cpumask * mask, smp_call_func_t func, void * info, bool wait)
```
</details>
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
