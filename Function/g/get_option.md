# Function: <code>get_option</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945104,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:52",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/cpu/common.c:setup_show_msr",
        "arch/x86/kernel/cpu/common.c:setup_disablecpuid",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:nrcpus",
        "kernel/smp.c:maxcpus",
        "mm/slub.c:setup_slub_min_order",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_objects",
        "lib/cmdline.c:get_options",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/char/hpet.c:hpet_mmap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945104,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232336,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:52",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/cpu/common.c:setup_disablecpuid",
        "arch/x86/kernel/cpu/common.c:setup_show_msr",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232336,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583347392,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:52",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/cpu/common.c:setup_disablecpuid",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347392,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588198400,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:53",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/cpu/common.c:setup_disablecpuid",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198400,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588747200,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:53",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747200,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589125008,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:53",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125008,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589359648,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:53",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589359648,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589816720,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816720,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590043040,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590043040,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585037212,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cmdline.c:get_options"
      ],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036864,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585188784,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:56",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585188784,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585071728,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:56",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071728,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585518416,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:56",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585518416,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670608,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:56",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670608,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595750016,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:56",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_pci",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595750016,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596274320,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:56",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_pci",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596274320,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597159056,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:56",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_pci",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "drivers/md/md-autodetect.c:md_setup",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597159056,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503803872,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503803872,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236426944,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/arm/plat-omap/dma.c:omap_dma_cmdline_reserve_ch",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236426944,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297642384,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/powerpc/kernel/rtasd.c:surveillance_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297642384,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279701176,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279701176,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589645296,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589645296,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589371168,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371168,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590088672,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088672,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int get_option(char * * str, int * pint)
```

```json
{
  "name": "get_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590138928,
      "name": "get_option",
      "external": true,
      "loc": "lib/cmdline.c:50",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:loglevel",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "init/do_mounts_md.c:md_setup",
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_enable",
        "arch/x86/kernel/smpboot.c:_setup_possible_cpus",
        "arch/x86/kernel/smpboot.c:cpu_init_udelay",
        "arch/x86/kernel/apic/apic.c:apic_set_disabled_cpu_apicid",
        "arch/x86/kernel/apic/ipi.c:apic_ipi_shorthand",
        "arch/x86/kernel/apic/vector.c:setup_show_lapic",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "arch/x86/kernel/amd_gart_64.c:gart_parse_options",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:reserve_setup",
        "kernel/signal.c:setup_print_fatal_signals",
        "kernel/printk/printk.c:boot_delay_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/profile.c:profile_setup",
        "kernel/time/tick-sched.c:skew_tick",
        "kernel/smp.c:maxcpus",
        "kernel/smp.c:nrcpus",
        "kernel/watchdog.c:watchdog_thresh_setup",
        "mm/slub.c:setup_slub_memcg_sysfs",
        "mm/slub.c:setup_slub_min_objects",
        "mm/slub.c:setup_slub_max_order",
        "mm/slub.c:setup_slub_min_order",
        "drivers/acpi/pci_link.c:acpi_irq_penalty_update",
        "drivers/pnp/resource.c:pnp_setup_reserve_mem",
        "drivers/pnp/resource.c:pnp_setup_reserve_io",
        "drivers/pnp/resource.c:pnp_setup_reserve_dma",
        "drivers/pnp/resource.c:pnp_setup_reserve_irq",
        "drivers/char/hpet.c:hpet_mmap_enable",
        "lib/cmdline.c:get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138928,
      "name": "get_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
