# Function: <code>__init_rwsem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679280,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem-xadd.c:73",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:sget_userns",
        "fs/inode.c:address_space_init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679280,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698368,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem-xadd.c:73",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:sget_userns",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698368,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725504,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem-xadd.c:73",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/auto_group.c:sched_autogroup_create_attach",
        "kernel/sched/auto_group.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:sget_userns",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725504,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721504,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem-xadd.c:75",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc_possible",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:sget_userns",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721504,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754208,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem-xadd.c:76",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc_possible",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754208,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579788624,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem-xadd.c:76",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc_possible",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/opp/core.c:dev_pm_opp_get_opp_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788624,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835088,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem-xadd.c:76",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc_possible",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:sget_userns",
        "fs/super.c:sget_userns",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835088,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859600,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:323",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_mirror_register",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859600,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908288,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908288,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952144,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:323",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_new_master_key",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "block/keyslot-manager.c:blk_ksm_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952144,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940560,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:304",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:copy_signal",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/inode.c:fuse_alloc_inode",
        "fs/fuse/dax.c:fuse_dax_inode_alloc",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/keyslot-manager.c:blk_ksm_init",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_create",
        "net/ipv4/nexthop.c:nexthop_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940560,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948272,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:304",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:copy_signal",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/inode.c:fuse_alloc_inode",
        "fs/fuse/dax.c:fuse_dax_inode_alloc",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/keyslot-manager.c:blk_ksm_init_passthrough",
        "block/keyslot-manager.c:blk_ksm_init",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/ipv4/nexthop.c:nexthop_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948272,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580077376,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:305",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:copy_signal",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/inode.c:inode_init_always",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/dax.c:fuse_dax_inode_alloc",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/keyslot-manager.c:blk_ksm_init_passthrough",
        "block/keyslot-manager.c:blk_ksm_init",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_init_device",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/ipv4/nexthop.c:nexthop_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077376,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580213216,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:305",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:copy_signal",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:inode_init_always",
        "fs/inode.c:inode_init_always",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/dax.c:fuse_dax_inode_alloc",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_init_device",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/ipv4/nexthop.c:nexthop_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580213216,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580405552,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:313",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:copy_signal",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/inode.c:inode_init_always",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/dax.c:fuse_dax_inode_alloc",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/ipv4/nexthop.c:nexthop_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405552,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474336,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:310",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:copy_signal",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:vm_area_dup",
        "kernel/fork.c:vm_area_alloc",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/inode.c:inode_init_always",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/configfs/dir.c:configfs_register_subsystem",
        "fs/configfs/dir.c:configfs_register_group",
        "fs/configfs/dir.c:configfs_mkdir",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/dax.c:fuse_dax_inode_alloc",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/ipv4/nexthop.c:nexthop_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474336,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534160,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:310",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:copy_signal",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:vm_area_dup",
        "kernel/fork.c:vm_area_alloc",
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:autogroup_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/events/uprobes.c:alloc_uprobe",
        "kernel/events/uprobes.c:alloc_uprobe",
        "mm/backing-dev.c:bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hugetlb.c:resv_map_alloc",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/inode.c:inode_init_always",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/dax.c:fuse_dax_inode_alloc",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/blk-crypto-profile.c:blk_crypto_profile_init",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/md/dm-table.c:dm_table_create",
        "drivers/opp/core.c:_add_opp_table_indexed",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/firmware/efi/efi.c:efisubsys_init",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/ipv4/nexthop.c:nexthop_net_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534160,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491109960,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491109960,
      "name": "__init_rwsem",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225113120,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "sound/core/init.c:snd_card_new",
        "sound/soc/soc-jack.c:snd_soc_card_jack_new",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225113120,
      "name": "__init_rwsem",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284001520,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284001520,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271689688,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "kernel/padata.c:padata_alloc_possible",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/opp/core.c:_opp_get_opp_table",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271689688,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880400,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880400,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815392,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815392,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868560,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868560,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __init_rwsem(struct rw_semaphore * sem, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__init_rwsem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579913984,
      "name": "__init_rwsem",
      "external": true,
      "loc": "kernel/locking/rwsem.c:324",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/sched/autogroup.c:sched_autogroup_create_attach",
        "kernel/sched/autogroup.c:autogroup_init",
        "kernel/locking/percpu-rwsem.c:__percpu_init_rwsem",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/power/qos.c:freq_constraints_init",
        "kernel/time/posix-clock.c:posix_clock_register",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/taskstats.c:taskstats_init_early",
        "mm/backing-dev.c:cgwb_bdi_init",
        "mm/rmap.c:anon_vma_ctor",
        "mm/hmm.c:hmm_alloc_notifier",
        "fs/super.c:alloc_super",
        "fs/super.c:alloc_super",
        "fs/inode.c:inode_init_once",
        "fs/inode.c:address_space_init_once",
        "fs/inode.c:inode_init_always",
        "fs/crypto/keyring.c:add_master_key",
        "fs/configfs/dir.c:new_fragment",
        "fs/ext4/mballoc.c:ext4_mb_add_groupinfo",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/ext4/super.c:init_once",
        "fs/fat/inode.c:fat_alloc_inode",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:ipc_init_ids",
        "security/keys/key.c:key_alloc",
        "block/genhd.c:__alloc_disk_node",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe",
        "drivers/regulator/core.c:regulator_register",
        "drivers/tty/tty_io.c:alloc_tty_struct",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/iommu.c:iommu_group_alloc",
        "drivers/base/bus.c:bus_register",
        "drivers/base/power/qos.c:dev_pm_qos_constraints_allocate",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/adp5520.c:adp5520_probe",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/vfio/vfio.c:vfio_fops_open",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_open",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "net/sched/cls_api.c:tcf_block_get_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913984,
      "name": "__init_rwsem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
