# Function: <code>kstrtobool</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583340016,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:333",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/usb/core/hcd.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340016,
      "name": "kstrtobool",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583465440,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:329",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/ksm.c:use_zero_pages_store",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/usb/core/hcd.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465440,
      "name": "kstrtobool",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583487728,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:331",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/ksm.c:use_zero_pages_store",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/usb/core/hcd.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487728,
      "name": "kstrtobool",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583668768,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/ksm.c:use_zero_pages_store",
        "fs/debugfs/file.c:debugfs_write_file_bool",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/hcd.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668768,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583886544,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/hcd.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886544,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583970752,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/hcd.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970752,
      "name": "kstrtobool",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584151920,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store",
        "drivers/pci/pcie/aspm.c:clk_ctl_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151920,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584274544,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "arch/x86/platform/uv/tlb_uv.c:setup_bau",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274544,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584683642,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtobool_from_user"
      ],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "arch/x86/platform/uv/tlb_uv.c:setup_bau",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584683392,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584801210,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:328",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtobool_from_user"
      ],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/reboot.c:force_store",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/input/input.c:inhibited_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/cpufreq/intel_pstate.c:store_energy_efficiency",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584800960,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584847786,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:335",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtobool_from_user"
      ],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "init/main.c:early_randomize_kstack_offset",
        "init/initramfs.c:initramfs_async_setup",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/reboot.c:force_store",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/input/input.c:inhibited_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/cpufreq/intel_pstate.c:store_energy_efficiency",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845136,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585267924,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:336",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtobool_from_user"
      ],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "init/main.c:early_randomize_kstack_offset",
        "init/initramfs.c:initramfs_async_setup",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/reboot.c:force_store",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/input/input.c:inhibited_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/cpufreq/intel_pstate.c:store_energy_efficiency",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585265056,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586109728,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:348",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "init/initramfs.c:initramfs_async_setup",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/signal.c:strict_sas_size",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/reboot.c:force_store",
        "kernel/sched/build_utility.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/swap_state.c:vma_ra_enabled_store",
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_early_param",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/migrate.c:numa_demotion_enabled_store",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "lib/stackdepot.c:is_stack_depot_disabled",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_bootloader",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/input/input.c:inhibited_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/cpufreq/intel_pstate.c:store_energy_efficiency",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109728,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587095344,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:348",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "init/initramfs.c:initramfs_async_setup",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:parse_xen_msr_safe",
        "arch/x86/kernel/signal.c:strict_sas_size",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/reboot.c:force_store",
        "kernel/sched/build_utility.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/swap_state.c:vma_ra_enabled_store",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/memory-tiers.c:numa_demotion_enabled_store",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "lib/stackdepot.c:is_stack_depot_disabled",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_bootloader",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:early_stop_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/input/input.c:inhibited_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/cpufreq/intel_pstate.c:store_energy_efficiency",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587095344,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587355424,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:348",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "init/initramfs.c:initramfs_async_setup",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:parse_xen_msr_safe",
        "arch/x86/kernel/signal.c:strict_sas_size",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/cpu.c:parallel_bringup_parse_param",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/reboot.c:force_store",
        "kernel/sched/build_utility.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/mm_init.c:early_init_on_free",
        "mm/mm_init.c:early_init_on_alloc",
        "mm/swap_state.c:vma_ra_enabled_store",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/memory-tiers.c:numa_demotion_enabled_store",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "lib/stackdepot.c:disable_stack_depot",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_bootloader",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup",
        "drivers/base/firmware_loader/sysfs_upload.c:cancel_store",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_cdl_enable",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:early_stop_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/input/input.c:inhibited_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/cpufreq/intel_pstate.c:store_energy_efficiency",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587355424,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587641744,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:348",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "init/initramfs.c:initramfs_async_setup",
        "arch/x86/entry/common.c:ia32_emulation_override_cmdline",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/enlighten_pv.c:parse_xen_msr_safe",
        "arch/x86/kernel/signal.c:strict_sas_size",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/cpu.c:parallel_bringup_parse_param",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/reboot.c:force_store",
        "kernel/sched/build_utility.c:setup_psi",
        "kernel/rcu/tree.c:param_set_do_rcu_barrier",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "kernel/cgroup/cgroup.c:cgroup_favordynmods_setup",
        "mm/mm_init.c:early_init_on_free",
        "mm/mm_init.c:early_init_on_alloc",
        "mm/memory_hotplug.c:set_memmap_mode",
        "mm/swap_state.c:vma_ra_enabled_store",
        "mm/ksm.c:smart_scan_store",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/memory-tiers.c:demotion_enabled_store",
        "mm/memcontrol.c:setup_swap_account",
        "mm/usercopy.c:parse_hardened_usercopy",
        "block/bdev.c:setup_bdev_allow_write_mounted",
        "lib/kstrtox.c:kstrtobool_from_user",
        "lib/stackdepot.c:disable_stack_depot",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/p2pdma.c:pci_p2pdma_enable_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/char/random.c:parse_trust_bootloader",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/base/core.c:fw_devlink_strict_setup",
        "drivers/base/firmware_loader/sysfs_upload.c:cancel_store",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/scsi/scsi_sysfs.c:sdev_store_cdl_enable",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_shutdown_store",
        "drivers/scsi/sd.c:manage_runtime_start_stop_store",
        "drivers/scsi/sd.c:manage_system_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:disable_store",
        "drivers/usb/core/port.c:early_stop_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/input/input.c:inhibited_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/cpufreq/intel_pstate.c:store_energy_efficiency",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587641744,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496159336,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/arm64/kernel/cpufeature.c:early_enable_pseudo_nmi",
        "arch/arm64/kernel/cpufeature.c:parse_kpti",
        "arch/arm64/mm/mmu.c:parse_rodata",
        "virt/kvm/arm/vgic/vgic-v3.c:early_gicv4_enable",
        "virt/kvm/arm/vgic/vgic-v3.c:early_common_trap_cfg",
        "virt/kvm/arm/vgic/vgic-v3.c:early_group1_trap_cfg",
        "virt/kvm/arm/vgic/vgic-v3.c:early_group0_trap_cfg",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg",
        "drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496159336,
      "name": "kstrtobool",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229480028,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg",
        "drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/roles/class.c:role_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229480028,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290423056,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:parse_ppc_tm",
        "arch/powerpc/kernel/rtasd.c:rtasmsgs_setup",
        "arch/powerpc/mm/init_64.c:parse_disable_radix",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:setup_cede_offline",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/region_devs.c:deep_flush_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290423056,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275211614,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275211614,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584243280,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/md/md.c:fail_last_dev_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243280,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584178480,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/md/md.c:fail_last_dev_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178480,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584227040,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227040,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtobool(const char * s, bool * res)
```

```json
{
  "name": "kstrtobool",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584331872,
      "name": "kstrtobool",
      "external": true,
      "loc": "lib/kstrtox.c:332",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:set_debug_rodata",
        "arch/x86/events/intel/core.c:set_sysctl_tfa",
        "arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/cpu/umwait.c:enable_c02_store",
        "arch/x86/kernel/aperture_64.c:parse_gart_mem",
        "arch/x86/platform/uv/tlb_uv.c:setup_bau",
        "kernel/params.c:param_set_bint",
        "kernel/params.c:param_set_invbool",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/params.c:param_set_bool_enable_only",
        "kernel/sched/psi.c:setup_psi",
        "kernel/livepatch/core.c:enabled_store",
        "kernel/time/hrtimer.c:setup_hrtimer_hres",
        "kernel/time/tick-sched.c:setup_tick_nohz",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/ksm.c:use_zero_pages_store",
        "mm/page_poison.c:early_page_poison_param",
        "mm/usercopy.c:parse_hardened_usercopy",
        "lib/kstrtox.c:kstrtobool_from_user",
        "drivers/pci/pcie/aspm.c:clkpm_store",
        "drivers/pci/iov.c:sriov_drivers_autoprobe_store",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store",
        "drivers/acpi/sysfs.c:force_remove_store",
        "drivers/char/random.c:parse_trust_cpu",
        "drivers/iommu/iommu.c:iommu_dma_setup",
        "drivers/iommu/iommu.c:iommu_set_def_domain_type",
        "drivers/base/core.c:online_store",
        "drivers/base/core.c:device_store_bool",
        "drivers/nvdimm/region_devs.c:read_only_store",
        "drivers/nvdimm/namespace_devs.c:force_raw_store",
        "drivers/dax/super.c:write_cache_store",
        "drivers/scsi/sd.c:allow_restart_store",
        "drivers/scsi/sd.c:manage_start_stop_store",
        "drivers/usb/core/sysfs.c:interface_authorized_store",
        "drivers/usb/core/sysfs.c:interface_authorized_default_store",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/input/serio/i8042.c:i8042_set_reset",
        "drivers/md/md.c:fail_last_dev_store",
        "drivers/powercap/powercap_sys.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331872,
      "name": "kstrtobool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int kstrtobool(const char * s, bool * res)
```
</details>
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
