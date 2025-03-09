# Function: <code>leave_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313376,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:41",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313376,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579312592,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:43",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312592,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579327808,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:43",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:xen_exit_mmap",
        "arch/x86/mm/tlb.c:flush_tlb_page",
        "arch/x86/mm/tlb.c:flush_tlb_mm_range",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327808,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322512,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:31",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322512,
      "name": "leave_mm",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346928,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:123",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346928,
      "name": "leave_mm",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358624,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:123",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358624,
      "name": "leave_mm",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386064,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:131",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386064,
      "name": "leave_mm",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:132",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403520,
      "name": "leave_mm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579401568,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579404832,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:132",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404832,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415232,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:288",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415232,
      "name": "leave_mm",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415424,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:287",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/kernel/alternative.c:__text_poke",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415424,
      "name": "leave_mm",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418368,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:288",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/kernel/alternative.c:__text_poke",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418368,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481792,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:295",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/kernel/alternative.c:__text_poke",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481792,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560224,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:296",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/kernel/alternative.c:__text_poke",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560224,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667536,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:296",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/kernel/alternative.c:__text_poke",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667536,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681424,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:301",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/kernel/alternative.c:__text_poke",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681424,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715872,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:302",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "arch/x86/kernel/alternative.c:__text_poke",
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715872,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400736,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:132",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400736,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579330176,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:132",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330176,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400656,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:132",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400656,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void leave_mm(int cpu)
```

```json
{
  "name": "leave_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409280,
      "name": "leave_mm",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:132",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu",
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter_bm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409280,
      "name": "leave_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void leave_mm(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void leave_mm(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void leave_mm(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void leave_mm(int cpu)
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
