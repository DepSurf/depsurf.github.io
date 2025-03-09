# Function: <code>x86_pmu_config_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578869041,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:703",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:perf_event_print_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889190,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:703",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594964935,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:703",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874538,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:712",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889589,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:712",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595128653,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:712",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874538,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:715",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889653,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:715",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595371461,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:715",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873787,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:720",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578889112,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:720",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596289598,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:720",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874850,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:728",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578890376,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:728",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602606386,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:728",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763788,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:731",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578891569,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:731",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602774708,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:731",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557926,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:749",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578891489,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:749",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604569540,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:749",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604652126,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:786",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578893041,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:786",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604664117,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:786",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604664398,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881954,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900588,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604676615,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int x86_pmu_config_addr(int index)
```

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578881431,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:811",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:reserve_pmc_hardware",
        "arch/x86/events/core.c:reserve_pmc_hardware"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:check_hw_exists"
      ]
    },
    {
      "addr": 18446744071578887856,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:811",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578903752,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:811",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609026681,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:811",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578974764,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:811",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578871120,
      "name": "x86_pmu_config_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int x86_pmu_config_addr(int index)
```

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578877517,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:942",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:reserve_pmc_hardware",
        "arch/x86/events/core.c:reserve_pmc_hardware"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:check_hw_exists"
      ]
    },
    {
      "addr": 18446744071578883382,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:942",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900112,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:942",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_workaround"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612090000,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:942",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977490,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:942",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578867392,
      "name": "x86_pmu_config_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int x86_pmu_config_addr(int index)
```

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578879517,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578885889,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578903586,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614229508,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986594,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181281,
      "name": "x86_pmu_config_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int x86_pmu_config_addr(int index)
```

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578883085,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578890257,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578905574,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615148144,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579002597,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1062",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592037426,
      "name": "x86_pmu_config_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned int x86_pmu_config_addr(int index)
```

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578880671,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1083",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578891193,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1083",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578910628,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1083",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616912944,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1083",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019261,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1083",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593803496,
      "name": "x86_pmu_config_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578885485,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1091",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897801,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1091",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578926148,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1091",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627510498,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1091",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046861,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1091",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883467,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1096",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578895689,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1096",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578924194,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1096",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619255410,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1096",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046877,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1096",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578905771,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1111",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:check_hw_exists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578918185,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1111",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_v2_enable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578946354,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1111",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621547986,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1111",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072205,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:1111",
      "file": "arch/x86/events/zhaoxin/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_enable_event",
        "arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590670,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881954,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900588,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604602887,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604582261,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578877204,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894316,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604594463,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668494,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578881890,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900524,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680711,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
  "name": "x86_pmu_config_addr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668499,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578882242,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578900988,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_guest_get_msrs",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604680731,
      "name": "x86_pmu_config_addr",
      "external": false,
      "loc": "arch/x86/events/perf_event.h:802",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int x86_pmu_config_addr(int index)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int x86_pmu_config_addr(int index)
```
</details>
</li>
</ul>
