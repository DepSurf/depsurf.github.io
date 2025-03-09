# Function: <code>kobject_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955616,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:569",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_remove",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elv_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-mq-sysfs.c:blk_mq_unregister_disk",
        "block/blk-integrity.c:blk_integrity_del",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kset_unregister",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955616,
      "name": "kobject_del",
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243344,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:569",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback",
        "mm/slub.c:sysfs_slab_remove",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elv_unregister_queue",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_unregister_disk",
        "block/blk-integrity.c:blk_integrity_del",
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kobject_release",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243344,
      "name": "kobject_del",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358656,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:569",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_remove",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elv_unregister_queue",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kobject_release",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358656,
      "name": "kobject_del",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588208959,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:569",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_put"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_remove_workfn",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "lib/kobject.c:kobject_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208768,
      "name": "kobject_del.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071588208832,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588758578,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:569",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_release"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_remove_workfn",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758416,
      "name": "kobject_del.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071588758480,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589136730,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:584",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_release"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136560,
      "name": "kobject_del.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071589136624,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589371770,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:584",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_release"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371600,
      "name": "kobject_del.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071589371664,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589828384,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589828384,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590054528,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590054528,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585050357,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:638",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:rdev_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050416,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585200149,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:635",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:rdev_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585200208,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585083221,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:635",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:rdev_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083280,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585530149,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:635",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elevator_switch_mq",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:rdev_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530208,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586684005,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:603",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elv_unregister_queue",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:rdev_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684080,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595764853,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:611",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elv_unregister_queue",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/class.c:__class_register",
        "drivers/md/md.c:rdev_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595764944,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596289253,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:612",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elv_unregister_queue",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/class.c:class_register",
        "drivers/md/md.c:mddev_unlock",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596289344,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597174117,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:619",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kset_unregister",
        "lib/kobject.c:kset_unregister"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/elevator.c:elv_unregister_queue",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_unregister",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_unregister_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "block/blk-ia-ranges.c:disk_register_independent_access_ranges",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/class.c:class_register",
        "drivers/md/md.c:mddev_unlock",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597174208,
      "name": "kobject_del",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503831280,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpuinfo.c:cpuid_cpu_offline",
        "arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/of/kobj.c:__of_detach_node_sysfs",
        "lib/kobject.c:kobject_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503831280,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236450964,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/of/kobj.c:__of_detach_node_sysfs",
        "lib/kobject.c:kobject_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236450964,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297678320,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/of/kobj.c:__of_detach_node_sysfs",
        "lib/kobject.c:kobject_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297678320,
      "name": "kobject_del",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279724106,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/of/kobj.c:__of_detach_node_sysfs",
        "lib/kobject.c:kobject_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279724106,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656784,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656784,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589382608,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589382608,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590100160,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590100160,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void kobject_del(struct kobject * kobj)
```

```json
{
  "name": "kobject_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590150480,
      "name": "kobject_del",
      "external": true,
      "loc": "lib/kobject.c:609",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device",
        "kernel/irq/irqdesc.c:free_desc",
        "mm/slub.c:sysfs_slab_unlink",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "mm/slub.c:sysfs_slab_add",
        "fs/ext4/sysfs.c:ext4_unregister_sysfs",
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_unregister_dev",
        "block/blk-integrity.c:blk_integrity_del",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:mddev_delayed_delete",
        "drivers/md/md.c:md_delayed_delete",
        "drivers/firmware/dmi_scan.c:dmi_init",
        "drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init",
        "lib/kobject.c:kobject_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590150480,
      "name": "kobject_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
