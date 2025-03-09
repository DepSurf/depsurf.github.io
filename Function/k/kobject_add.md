# Function: <code>kobject_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582958496,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:394",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582958496,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245952,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:394",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_register_disk",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245952,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583361264,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:394",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361264,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588211472,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:394",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211472,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761040,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:394",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761040,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:410",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140503,
      "name": "kobject_add.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071589139760,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:410",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375331,
      "name": "kobject_add.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071589374192,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589832501,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071589831328,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058645,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071590057472,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054104,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585052768,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks",
        "arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381791,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585202560,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324200,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585085632,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342293,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585532560,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:394",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "lib/kobject.c:kobject_create_and_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594203881,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586686416,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595767488,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:402",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595767488,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596291888,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:403",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596291888,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597176800,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:410",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank",
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/livepatch/core.c:klp_enable_patch",
        "kernel/livepatch/core.c:klp_init_object",
        "kernel/livepatch/core.c:klp_init_object",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:blk_mq_sysfs_register",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597176800,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503834288,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online",
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503834288,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236453784,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236453784,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297683424,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init",
        "arch/powerpc/platforms/powernv/opal-elog.c:elog_event",
        "arch/powerpc/platforms/powernv/opal-dump.c:process_dump",
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297683424,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279726658,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:get_device_parent",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/of/kobj.c:__of_attach_node_sysfs",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279726658,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660901,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071589659728,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386725,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071589385552,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104277,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071590103104,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int kobject_add(struct kobject * kobj, struct kobject * parent, const char * fmt, void (anon))
```

```json
{
  "name": "kobject_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kobject_add",
      "external": true,
      "loc": "lib/kobject.c:426",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_add",
        "block/elevator.c:elv_register_queue",
        "block/blk-sysfs.c:blk_register_queue",
        "block/blk-mq-sysfs.c:__blk_mq_register_dev",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "block/blk-mq-sysfs.c:blk_mq_register_hctx",
        "drivers/base/core.c:device_add",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/firmware/memmap.c:add_sysfs_fw_map_entry",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "lib/kobject.c:kobject_create_and_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154584,
      "name": "kobject_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071590153408,
      "name": "kobject_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
