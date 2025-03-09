# Function: <code>get_zeroed_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580490624,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:3277",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/swap.c:swsusp_write",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/super.c:mount_fs",
        "fs/kernfs/symlink.c:kernfs_iop_follow_link",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/hooks.c:selinux_sb_copy_data",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:alloc_new_range",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_update_state",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490624,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580575584,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:3745",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/super.c:mount_fs",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_copy_data",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_startup",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_update_state",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575584,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641984,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:3886",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/super.c:mount_fs",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_copy_data",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/net/xen-netfront.c:xennet_connect",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641984,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674416,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4173",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/super.c:mount_fs",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_copy_data",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674416,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759776,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4292",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/super.c:mount_fs",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_copy_data",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759776,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895632,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4424",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/super.c:mount_fs",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/hooks.c:selinux_sb_remount",
        "security/selinux/hooks.c:selinux_sb_copy_data",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/smack/smack_lsm.c:smack_sb_copy_data",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895632,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970464,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4598",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970464,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388304,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4765",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388304,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449248,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449248,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655584,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4886",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_vsyscall_time_info",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:get_swap_writer",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__p4d_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/iommu.c:increase_address_space",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655584,
      "name": "get_zeroed_page",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702976,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:5037",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_setup_vsyscall_time_info",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__p4d_alloc",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/iommu.c:increase_address_space",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702976,
      "name": "get_zeroed_page",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724592,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:5238",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__p4d_alloc",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724592,
      "name": "get_zeroed_page",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997968,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:5427",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__p4d_alloc",
        "fs/configfs/file.c:configfs_read_iter",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/net/xen-netfront.c:setup_netfront",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997968,
      "name": "get_zeroed_page",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421600,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:5482",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__p4d_alloc",
        "fs/libfs.c:simple_transaction_get",
        "fs/configfs/file.c:configfs_read_iter",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421600,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928912,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:5606",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__p4d_alloc",
        "fs/libfs.c:simple_transaction_get",
        "fs/configfs/file.c:configfs_read_iter",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928912,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145792,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4534",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:__p4d_alloc",
        "fs/libfs.c:simple_transaction_get",
        "fs/configfs/file.c:configfs_read_iter",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_make_bools",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145792,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583329616,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4623",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:alloc_pmd_page",
        "arch/x86/mm/pat/set_memory.c:alloc_pte_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/ftrace.c:ftrace_profile_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__p4d_alloc",
        "fs/libfs.c:simple_transaction_get",
        "fs/configfs/file.c:configfs_read_iter",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/iommu/amd/iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329616,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492855816,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/vdso.c:aarch32_alloc_vdso_pages",
        "arch/arm64/kernel/vdso.c:aarch32_alloc_vdso_pages",
        "arch/arm/xen/enlighten.c:xen_guest_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492855816,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226679736,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226679736,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286245184,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot",
        "arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286245184,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272821460,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/tty/serial/serial_core.c:uart_port_startup",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272821460,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418096,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418096,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581360608,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:populate_pgd",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "drivers/hv/hv.c:hv_synic_alloc",
        "drivers/hv/hv.c:hv_synic_alloc",
        "drivers/hv/hv.c:hv_synic_alloc",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360608,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409296,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409296,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
long unsigned int get_zeroed_page(gfp_t gfp_mask)
```

```json
{
  "name": "get_zeroed_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473392,
      "name": "get_zeroed_page",
      "external": true,
      "loc": "mm/page_alloc.c:4783",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/pmu.c:xen_pmu_init",
        "arch/x86/kernel/ldt.c:alloc_ldt_struct",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init",
        "arch/x86/mm/init_64.c:spp_getpage",
        "arch/x86/mm/pageattr.c:alloc_pmd_page",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "kernel/power/snapshot.c:snapshot_write_next",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/snapshot.c:get_image_page",
        "kernel/power/swap.c:swsusp_write",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/trace/tracing_map.c:tracing_map_array_alloc",
        "mm/memory.c:__pud_alloc",
        "mm/slub.c:__kmem_cache_create",
        "fs/configfs/file.c:configfs_read_file",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "security/selinux/selinuxfs.c:sel_read_bool",
        "security/selinux/selinuxfs.c:sel_make_policy_nodes",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "drivers/xen/events/events_base.c:set_evtchn_to_irq",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/tty/tty_port.c:tty_port_alloc_xmit_buf",
        "drivers/iommu/amd_iommu.c:__get_gcr3_pte",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/iommu/amd_iommu.c:iommu_map_page",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/net/xen-netfront.c:talk_to_netback",
        "drivers/usb/host/ohci-hcd.c:debug_output",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/extcon/extcon.c:extcon_sync",
        "drivers/ras/cec.c:cec_init",
        "net/core/dev.c:dev_alloc_name_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473392,
      "name": "get_zeroed_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
