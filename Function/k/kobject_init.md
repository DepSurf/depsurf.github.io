# Function: <code>kobject_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582955008,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:325",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_alloc",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582955008,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242592,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:325",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_alloc",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242592,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583357904,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:325",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/padata.c:padata_alloc",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357904,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588208336,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:325",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/padata.c:padata_alloc_possible",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588208336,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757680,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:325",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/padata.c:padata_alloc_possible",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757680,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:341",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/padata.c:padata_alloc_possible",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140342,
      "name": "kobject_init.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589135872,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:341",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/padata.c:padata_alloc_possible",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375190,
      "name": "kobject_init.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589370720,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589832359,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589827568,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058503,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071590053712,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585052990,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_create_and_add"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_object_nops",
        "kernel/livepatch/core.c:klp_add_object_nops",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:__blk_alloc_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/memmap.c:firmware_map_add_entry",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053962,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585048912,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585202782,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_create_and_add"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_object_nops",
        "kernel/livepatch/core.c:klp_add_object_nops",
        "kernel/padata.c:padata_alloc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/memmap.c:firmware_map_add_entry",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381649,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585198704,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585085854,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_create_and_add"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/padata.c:padata_alloc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/memmap.c:firmware_map_add_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324058,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585081776,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585532782,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_create_and_add"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/padata.c:padata_alloc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/memmap.c:firmware_map_add_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342151,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585528720,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kobject_init(struct kobject * kobj, const struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586686689,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:317",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject.c:kobject_create_and_add"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/padata.c:padata_alloc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "lib/kobject.c:kobject_init_and_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/memmap.c:firmware_map_add_entry",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594203740,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071586682512,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void kobject_init(struct kobject * kobj, const struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595763360,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:325",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/padata.c:padata_alloc",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/memmap.c:firmware_map_add_early",
        "drivers/firmware/memmap.c:firmware_map_add_hotplug",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595763360,
      "name": "kobject_init",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kobject_init(struct kobject * kobj, const struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596287744,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:326",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/padata.c:padata_alloc",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/memmap.c:firmware_map_add_early",
        "drivers/firmware/memmap.c:firmware_map_add_hotplug",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596287744,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void kobject_init(struct kobject * kobj, const struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597172608,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:333",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/irq/irqdesc.c:alloc_desc",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/livepatch/core.c:klp_add_nops",
        "kernel/padata.c:padata_alloc",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_import_device",
        "drivers/firmware/memmap.c:firmware_map_add_early",
        "drivers/firmware/memmap.c:firmware_map_add_hotplug",
        "lib/kobject.c:kobject_create_and_add",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597172608,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503829688,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpuinfo.c:cpuinfo_regs_init",
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/of/dynamic.c:__of_node_dup",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503829688,
      "name": "kobject_init",
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236449820,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/of/dynamic.c:__of_node_dup",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236449820,
      "name": "kobject_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297676704,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init",
        "arch/powerpc/platforms/powernv/opal-elog.c:elog_event",
        "arch/powerpc/platforms/powernv/opal-dump.c:process_dump",
        "arch/powerpc/platforms/pseries/reconfig.c:ofdt_write",
        "arch/powerpc/platforms/pseries/dlpar.c:dlpar_parse_cc_node",
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/of/dynamic.c:__of_node_dup",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297676704,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279722780,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/padata.c:padata_alloc_possible",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:get_device_parent",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/of/dynamic.c:__of_node_dup",
        "drivers/of/fdt.c:unflatten_dt_nodes",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279722780,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660759,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589655968,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386583,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071589381792,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104135,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071590099344,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void kobject_init(struct kobject * kobj, struct kobj_type * ktype)
```

```json
{
  "name": "kobject_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_init",
      "external": true,
      "loc": "lib/kobject.c:349",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:alloc_desc",
        "mm/slub.c:sysfs_slab_add",
        "fs/char_dev.c:cdev_init",
        "fs/char_dev.c:cdev_alloc",
        "block/elevator.c:elevator_alloc",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_init",
        "block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init",
        "drivers/base/core.c:device_initialize",
        "drivers/md/md.c:md_import_device",
        "drivers/md/md.c:mddev_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create",
        "lib/kobject.c:kobject_init_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154442,
      "name": "kobject_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071590149808,
      "name": "kobject_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobj_type * ktype</code> ➡️ <code>const struct kobj_type * ktype</code>
</li>
</ul>
</details>
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
