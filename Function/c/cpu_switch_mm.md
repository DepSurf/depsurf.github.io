# Function: <code>cpu_switch_mm</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cpu_switch_mm(pgd_t * pgd, struct mm_struct * mm)
```

```json
{
  "name": "cpu_switch_mm",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510816780,
      "name": "cpu_switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:49",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490262444,
      "name": "cpu_switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:49",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:cpu_enable_cnp",
        "arch/arm64/kernel/cpufeature.c:cpu_enable_cnp",
        "arch/arm64/kernel/cpufeature.c:cpu_enable_cnp",
        "arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings",
        "arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings",
        "arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cpu_switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:49",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490314436,
      "name": "cpu_switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:49",
      "file": "arch/arm64/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit",
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit",
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit",
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit",
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490327480,
      "name": "cpu_switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:49",
      "file": "arch/arm64/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/machine_kexec.c:machine_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490350540,
      "name": "cpu_switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:49",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init"
      ]
    },
    {
      "addr": 18446603336490351752,
      "name": "cpu_switch_mm",
      "external": false,
      "loc": "arch/arm64/include/asm/mmu_context.h:49",
      "file": "arch/arm64/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490350540,
      "name": "cpu_switch_mm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void cpu_switch_mm(pgd_t * pgd, struct mm_struct * mm)
```
</details>
</li>
</ul>
