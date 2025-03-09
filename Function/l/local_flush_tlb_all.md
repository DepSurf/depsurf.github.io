# Function: <code>local_flush_tlb_all</code>

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
void local_flush_tlb_all()
```

```json
{
  "name": "local_flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510816652,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:131",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490262380,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:131",
      "file": "arch/arm64/kernel/cpufeature.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cpufeature.c:cpu_enable_cnp",
        "arch/arm64/kernel/cpufeature.c:cpu_enable_cnp",
        "arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings",
        "arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490271380,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:131",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:secondary_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490314176,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:131",
      "file": "arch/arm64/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit",
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit",
        "arch/arm64/kernel/suspend.c:__cpu_suspend_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490327408,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:131",
      "file": "arch/arm64/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/machine_kexec.c:machine_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490350400,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:131",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/mmu.c:paging_init"
      ]
    },
    {
      "addr": 18446603336490351444,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm64/include/asm/tlbflush.h:131",
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
      "addr": 18446603336490350400,
      "name": "local_flush_tlb_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "local_flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224443872,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/suspend.c:cpu_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3224447628,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:secondary_start_kernel",
        "arch/arm/kernel/smp.c:__cpu_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3224451976,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/kernel/smp_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_all"
      ],
      "caller_func": []
    },
    {
      "addr": 3224497868,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/mm/idmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/idmap.c:setup_mm_for_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 3243284312,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/mmu.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224511508,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3224571892,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/mach-mvebu/pmsu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224576164,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/mach-imx/pm-imx5.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224585464,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/arm/include/asm/tlbflush.h:333",
      "file": "arch/arm/mach-imx/pm-imx6.c",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "local_flush_tlb_all",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270611954,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/riscv/include/asm/tlbflush.h:13",
      "file": "arch/riscv/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smpboot.c:smp_callin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270613984,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/riscv/include/asm/tlbflush.h:13",
      "file": "arch/riscv/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271360430,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/riscv/include/asm/tlbflush.h:13",
      "file": "arch/riscv/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/context.c:switch_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271361174,
      "name": "local_flush_tlb_all",
      "external": false,
      "loc": "arch/riscv/include/asm/tlbflush.h:13",
      "file": "arch/riscv/mm/tlbflush.c",
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
void local_flush_tlb_all()
```
</details>
</li>
</ul>
