# Function: <code>__sync_cache_range_w</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void __sync_cache_range_w(volatile void * p, size_t size)
```

```json
{
  "name": "__sync_cache_range_w",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243265560,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/setup.c:setup_arch"
      ],
      "caller_func": []
    },
    {
      "addr": 3224443608,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/kernel/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/suspend.c:cpu_suspend_alloc_sp"
      ],
      "caller_func": []
    },
    {
      "addr": 3224446524,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:__cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3224525920,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/common/mcpm_entry.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down",
        "arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down",
        "arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down",
        "arch/arm/common/mcpm_entry.c:mcpm_set_early_poke",
        "arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical",
        "arch/arm/common/mcpm_entry.c:__mcpm_outbound_enter_critical"
      ],
      "caller_func": [
        "arch/arm/common/mcpm_entry.c:nocache_trampoline",
        "arch/arm/common/mcpm_entry.c:nocache_trampoline",
        "arch/arm/common/mcpm_entry.c:nocache_trampoline",
        "arch/arm/common/mcpm_entry.c:nocache_trampoline",
        "arch/arm/common/mcpm_entry.c:mcpm_sync_init",
        "arch/arm/common/mcpm_entry.c:mcpm_sync_init"
      ]
    },
    {
      "addr": 3224561332,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/mach-exynos/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary",
        "arch/arm/mach-exynos/platsmp.c:exynos_secondary_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243298440,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/mach-hisi/platmcpm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-hisi/platmcpm.c:hip04_smp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243301736,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/mach-mvebu/coherency.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-mvebu/coherency.c:coherency_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243308252,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/mach-imx/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/platsmp.c:imx_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3224687644,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/mach-vexpress/spc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-vexpress/spc.c:ve_spc_init",
        "arch/arm/mach-vexpress/spc.c:ve_spc_init"
      ]
    },
    {
      "addr": 3224697556,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "arch/arm/plat-versatile/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/plat-versatile/platsmp.c:versatile_boot_secondary",
        "arch/arm/plat-versatile/platsmp.c:versatile_secondary_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3229758860,
      "name": "__sync_cache_range_w",
      "external": false,
      "loc": "arch/arm/include/asm/cacheflush.h:392",
      "file": "drivers/bus/arm-cci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/arm-cci.c:cci_probe_ports",
        "drivers/bus/arm-cci.c:cci_probe_ports",
        "drivers/bus/arm-cci.c:cci_probe_ports",
        "drivers/bus/arm-cci.c:cci_probe_ports",
        "drivers/bus/arm-cci.c:cci_probe_ports"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224524644,
      "name": "__sync_cache_range_w",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3224687644,
      "name": "__sync_cache_range_w",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3229758860,
      "name": "__sync_cache_range_w",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __sync_cache_range_w(volatile void * p, size_t size)
```
</details>
</li>
</ul>
