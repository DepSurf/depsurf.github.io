# Function: <code>add_taint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372448,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:307",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_args",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_bug",
        "lib/bug.c:report_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372448,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380176,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:356",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_args",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page_alloc.c:bad_page",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380176,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399216,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:386",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_args",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page_alloc.c:bad_page",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399216,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386560,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:388",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_attr_store",
        "kernel/params.c:parse_args",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/page_alloc.c:bad_page",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386560,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413440,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:393",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page_alloc.c:bad_page",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413440,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:382",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page_alloc.c:bad_page",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429169,
      "name": "add_taint.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579427904,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:417",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/page_alloc.c:bad_page",
        "mm/memory.c:print_bad_pte",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462769,
      "name": "add_taint.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579461328,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579480327,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:422",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480692,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579479552,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506207,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506580,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579505440,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579535550,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:441",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:set_license",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535533,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579533856,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591277686,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:441",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_module_license_and_versions",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:set_license",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591277669,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579516784,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591220584,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:441",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591220567,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579519936,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592099119,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:439",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:check_bytes_and_report",
        "mm/slub.c:slab_err",
        "mm/slub.c:object_err",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592099102,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071579591648,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:483",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_check_unsafe",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:check_bytes_and_report",
        "mm/slub.c:slab_err",
        "mm/slub.c:object_err",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/vfio/vfio.c:vfio_register_group_dev",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593866446,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579683168,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805520,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:534",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_check_unsafe",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:load_module",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/module/main.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:deactivate_slab",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:on_freelist",
        "mm/slub.c:check_object",
        "mm/slub.c:check_bytes_and_report",
        "mm/slub.c:slab_err",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805520,
      "name": "add_taint",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579853616,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:534",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_check_unsafe",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:deactivate_slab",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:on_freelist",
        "mm/slub.c:check_object",
        "mm/slub.c:check_bytes_and_report",
        "mm/slub.c:slab_err",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:device_to_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853616,
      "name": "add_taint",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891424,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:538",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/params.c:param_check_unsafe",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/module/main.c:module_augment_kernel_taints",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:deactivate_slab",
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:on_freelist",
        "mm/slub.c:check_object",
        "mm/slub.c:check_bytes_and_report",
        "mm/slub.c:slab_err",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/pci/pci-sysfs.c:pci_write_config",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/intel/dmar.c:warn_invalid_dmar",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa",
        "drivers/iommu/intel/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr",
        "drivers/iommu/intel/iommu.c:device_lookup_iommu",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar",
        "arch/x86/pci/common.c:pcibios_setup",
        "arch/x86/pci/common.c:pcibios_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891424,
      "name": "add_taint",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490639728,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:die",
        "arch/arm64/kernel/cpufeature.c:update_cpu_features",
        "kernel/panic.c:__warn",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:gic_check_reserved_range",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490639728,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224716552,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/traps.c:die",
        "arch/arm/mm/mmu.c:early_mm_init",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init",
        "drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis",
        "drivers/irqchip/irq-gic-v3-its.c:gic_check_reserved_range",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224716552,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283459800,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:machine_check_exception",
        "arch/powerpc/kernel/traps.c:machine_check_exception",
        "arch/powerpc/kernel/traps.c:system_reset_exception",
        "arch/powerpc/kernel/mce.c:machine_check_process_queued_event",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283457488,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271394002,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/riscv/kernel/traps.c:die",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/module.c:layout_and_allocate",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271392434,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479871,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480244,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579479104,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579408767,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409140,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579408000,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479791,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480164,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579479024,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok)
```

```json
{
  "name": "add_taint",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579511647,
      "name": "add_taint",
      "external": true,
      "loc": "kernel/panic.c:431",
      "file": "kernel/panic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "kernel/sysctl.c:proc_taint",
        "kernel/sched/core.c:__schedule_bug",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:load_module",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/module.c:check_modinfo",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/memory.c:print_bad_pte",
        "mm/page_alloc.c:bad_page",
        "mm/slub.c:slab_bug",
        "drivers/pci/pci-sysfs.c:numa_node_store",
        "drivers/iommu/dmar.c:warn_invalid_dmar",
        "drivers/iommu/dmar.c:dmar_parse_one_andd",
        "drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu",
        "drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file",
        "drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512020,
      "name": "add_taint.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579510880,
      "name": "add_taint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
