# Function: <code>kstrdup_const</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597376,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:69",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "lib/kobject.c:kobject_rename",
        "lib/dynamic_debug.c:ddebug_add_module",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_class.c:alloc_fw_cache_entry",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597376,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698368,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:69",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kobject.c:kobject_rename",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/dynamic_debug.c:ddebug_add_module",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_class.c:alloc_fw_cache_entry",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698368,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764144,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:69",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kobject.c:kobject_rename",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/dynamic_debug.c:ddebug_add_module",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_class.c:alloc_fw_cache_entry",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:_request_firmware"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764144,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800416,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:72",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/dynamic_debug.c:ddebug_add_module",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_class.c:alloc_fw_cache_entry",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800416,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889120,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:72",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/dynamic_debug.c:ddebug_add_module",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_class.c:alloc_fw_cache_entry",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/base/firmware_class.c:assign_firmware_buf",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889120,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025040,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:72",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/dynamic_debug.c:ddebug_add_module",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025040,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102560,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:65",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/dynamic_debug.c:ddebug_add_module",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102560,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166816,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:70",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166816,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224608,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224608,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412176,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:create_new_subsystem",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kobject.c:kobject_rename",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_device_cell_write",
        "drivers/nvmem/core.c:nvmem_device_cell_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412176,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454848,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:78",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:create_new_subsystem",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kobject.c:kobject_rename",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_add_cells_from_table",
        "drivers/nvmem/core.c:nvmem_add_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454848,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475728,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:78",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kobject.c:kobject_rename",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475728,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729792,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:78",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_hist.c:create_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:init_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kobject.c:kobject_rename",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729792,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109392,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:79",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_hist.c:create_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:init_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kobject.c:kobject_rename",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_cells",
        "drivers/hte/hte.c:hte_init_line_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109392,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584736,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:79",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_hist.c:create_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:init_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_cells",
        "drivers/hte/hte.c:hte_init_line_attr",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584736,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582791856,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:80",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_hist.c:create_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:init_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/leds/led-class.c:led_get",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_one_cell",
        "drivers/hte/hte.c:hte_init_line_attr",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791856,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582966896,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:80",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create_systems",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events_hist.c:create_var",
        "kernel/trace/trace_events_hist.c:parse_expr",
        "kernel/trace/trace_events_hist.c:parse_unary",
        "kernel/trace/trace_events_hist.c:init_var_ref",
        "kernel/trace/trace_events_hist.c:create_hist_field",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "fs/tracefs/event_inode.c:eventfs_create_events_dir",
        "fs/tracefs/event_inode.c:eventfs_create_dir",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:dev_create_fw_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:fw_add_devm_name",
        "drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/gpu/drm/drm_managed.c:drmm_kmalloc",
        "drivers/gpu/drm/drm_managed.c:__drmm_add_action",
        "drivers/leds/led-class.c:led_get",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_one_cell",
        "drivers/hte/hte.c:hte_init_line_attr",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582966896,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492613232,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pinctrl/devicetree.c:dt_remember_or_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492613232,
      "name": "kstrdup_const",
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226464992,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pinctrl/devicetree.c:dt_remember_or_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226464992,
      "name": "kstrdup_const",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285930336,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pinctrl/devicetree.c:dt_remember_or_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285930336,
      "name": "kstrdup_const",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272639744,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/pinctrl/devicetree.c:dt_remember_or_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272639744,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193456,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193456,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140208,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140208,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184656,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184656,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
const char * kstrdup_const(const char * s, gfp_t gfp)
```

```json
{
  "name": "kstrdup_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247904,
      "name": "kstrdup_const",
      "external": true,
      "loc": "mm/util.c:77",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kasprintf.c:kvasprintf_const",
        "lib/kasprintf.c:kvasprintf_const",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/acpi/scan.c:acpi_add_id",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:alloc_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:alloc_fw_cache_entry",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:_request_firmware",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell",
        "lib/kobject.c:kobject_rename"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247904,
      "name": "kstrdup_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
