# Function: <code>__printk_ratelimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724704,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:2776",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sysctl_binary.c:do_sysctl",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/audit.c:audit_printk_skb",
        "kernel/audit.c:audit_log_start",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/policy_ns.c:alloc_ns",
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "lib/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724704,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579744480,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:2918",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sysctl_binary.c:do_sysctl",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_printk_skb",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "lib/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579744480,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771824,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:2750",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sysctl_binary.c:do_sysctl",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:aa_free_profile",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "security/apparmor/label.c:aa_label_xprintk",
        "security/apparmor/label.c:aa_label_seq_xprint",
        "security/apparmor/label.c:aa_label_xaudit",
        "security/apparmor/label.c:aa_label_alloc",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/policy_ns.c:__aa_create_ns",
        "security/apparmor/policy_ns.c:alloc_ns",
        "lib/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771824,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768400,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:2757",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "lib/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768400,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801488,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:2751",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "lib/swiotlb.c:swiotlb_alloc_coherent",
        "lib/swiotlb.c:swiotlb_tbl_map_single",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801488,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834976,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:2928",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_alloc",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/acpi/apei/ghes.c:ghes_read_estatus",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834976,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881744,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:2940",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/hooks.c:inode_doinit_with_dentry",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/vt/keyboard.c:kbd_event",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881744,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916320,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3005",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/pci/pci.c:pci_raw_set_power_state",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916320,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966368,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966368,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013168,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3083",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013168,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991360,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3162",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_timer_reinit",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/iommu/amd/iommu.c:amd_iommu_report_page_fault",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991360,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993104,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3226",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993104,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580125104,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3290",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125104,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580266896,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3546",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:gp_user_force_sig_segv",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266896,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472688,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3809",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/signal.c:get_sigframe",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472688,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580544272,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3850",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/signal.c:get_sigframe",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544272,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580606160,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3968",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/signal.c:get_sigframe",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:kauditd_hold_skb",
        "kernel/audit.c:audit_log_lost",
        "mm/vmalloc.c:alloc_vmap_area",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_receive_byte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606160,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491146960,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491146960,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225177224,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl_binary.c:__se_sys_sysctl",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/ata/libahci.c:ahci_read_em_buffer",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt",
        "sound/core/pcm_lib.c:snd_pcm_update_hw_ptr0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225177224,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284043424,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/iommu.c:iommu_map_page",
        "arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg",
        "arch/powerpc/kernel/iommu.c:__iommu_free",
        "arch/powerpc/kernel/iommu.c:iommu_range_alloc",
        "arch/powerpc/platforms/pseries/iommu.c:tce_get_pSeriesLP",
        "arch/powerpc/platforms/pseries/iommu.c:tce_free_pSeriesLP",
        "arch/powerpc/perf/core-book3s.c:perf_event_interrupt",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284043424,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271704820,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:do_trap",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271704820,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935104,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935104,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873376,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873376,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926640,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926640,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __printk_ratelimit(const char * func)
```

```json
{
  "name": "__printk_ratelimit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972624,
      "name": "__printk_ratelimit",
      "external": true,
      "loc": "kernel/printk/printk.c:3015",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/irq.c:ack_bad_irq",
        "arch/x86/kernel/hpet.c:hpet_rtc_interrupt",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "kernel/sched/core.c:select_fallback_rq",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/dma/swiotlb.c:swiotlb_tbl_map_single",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/cma.c:cma_alloc",
        "fs/quota/dquot.c:__quota_error",
        "security/selinux/ss/services.c:context_struct_compute_av",
        "drivers/acpi/apei/erst.c:pr_unimpl_nvram",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/vt/keyboard.c:kbd_keycode",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/iommu/amd_iommu.c:amd_iommu_int_thread",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/input/keyboard/atkbd.c:atkbd_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972624,
      "name": "__printk_ratelimit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
