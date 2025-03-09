# Function: <code>kfree_const</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597232,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:32",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:slab_kmem_cache_release",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/dynamic_debug.c:ddebug_remove_module",
        "lib/dynamic_debug.c:dynamic_debug_init",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/base/power/wakeup.c:wakeup_source_destroy",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:__fw_free_buf",
        "drivers/base/firmware_class.c:dev_cache_fw_image",
        "drivers/base/firmware_class.c:device_uncache_fw_images_work",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597232,
      "name": "kfree_const",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698224,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:32",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/dynamic_debug.c:dynamic_debug_init",
        "lib/dynamic_debug.c:ddebug_remove_module",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/base/power/wakeup.c:wakeup_source_destroy",
        "drivers/base/firmware_class.c:device_uncache_fw_images_work",
        "drivers/base/firmware_class.c:dev_cache_fw_image",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:__fw_free_buf",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698224,
      "name": "kfree_const",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764000,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:32",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/dynamic_debug.c:dynamic_debug_init",
        "lib/dynamic_debug.c:ddebug_remove_module",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/base/power/wakeup.c:wakeup_source_destroy",
        "drivers/base/firmware_class.c:device_uncache_fw_images_work",
        "drivers/base/firmware_class.c:dev_cache_fw_image",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:__fw_free_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764000,
      "name": "kfree_const",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800272,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:35",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/dynamic_debug.c:dynamic_debug_init",
        "lib/dynamic_debug.c:ddebug_remove_module",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/firmware_class.c:device_uncache_fw_images_work",
        "drivers/base/firmware_class.c:dev_cache_fw_image",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_free_buf",
        "lib/kobject.c:kobject_put",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800272,
      "name": "kfree_const",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888976,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:35",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/dynamic_debug.c:dynamic_debug_init",
        "lib/dynamic_debug.c:ddebug_remove_module",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/firmware_class.c:device_uncache_fw_images_work",
        "drivers/base/firmware_class.c:dev_cache_fw_image",
        "drivers/base/firmware_class.c:request_firmware_nowait",
        "drivers/base/firmware_class.c:request_firmware_work_func",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:fw_name_devm_release",
        "drivers/base/firmware_class.c:__fw_free_buf",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888976,
      "name": "kfree_const",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024896,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:35",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/dynamic_debug.c:dynamic_debug_init",
        "lib/dynamic_debug.c:ddebug_remove_module",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024896,
      "name": "kfree_const",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102416,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:28",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/dynamic_debug.c:dynamic_debug_init",
        "lib/dynamic_debug.c:ddebug_remove_module",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:clk_register",
        "drivers/clk/clk.c:__clk_free_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102416,
      "name": "kfree_const",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166672,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:30",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166672,
      "name": "kfree_const",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224464,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224464,
      "name": "kfree_const",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412032,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:create_new_subsystem",
        "kernel/trace/trace_events.c:__put_system",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:delayed_free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:__device_uncache_fw_images",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_init_cache_dev",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "drivers/interconnect/core.c:icc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412032,
      "name": "kfree_const",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454704,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:create_new_subsystem",
        "kernel/trace/trace_events.c:__put_system",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:delayed_free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:destroy_regulator",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:__device_uncache_fw_images",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_init_cache_dev",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "drivers/interconnect/core.c:icc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454704,
      "name": "kfree_const",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475584,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events.c:__put_system",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/clk.c:clk_core_populate_parent_map",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "drivers/interconnect/core.c:icc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475584,
      "name": "kfree_const",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729648,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events.c:__put_system",
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:create_var_field",
        "kernel/trace/trace_events_hist.c:create_var",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "drivers/interconnect/core.c:icc_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729648,
      "name": "kfree_const",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109232,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:38",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events.c:__put_system",
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_var",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:__acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_entry_drop",
        "drivers/interconnect/core.c:icc_put",
        "drivers/hte/hte.c:hte_ts_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109232,
      "name": "kfree_const",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582896,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:38",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events.c:__put_system",
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_var",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/char_dev.c:cdev_add",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/class.c:__class_register",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_cell_entry_drop",
        "drivers/interconnect/core.c:icc_put",
        "drivers/hte/hte.c:hte_ts_put",
        "lib/kobject.c:kset_register",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582896,
      "name": "kfree_const",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790000,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:38",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events.c:__put_system",
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_var",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/char_dev.c:cdev_add",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:delayed_free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodev_release",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/class.c:class_register",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/leds/led-class.c:led_get",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:nvmem_cell_read_common",
        "drivers/nvmem/core.c:devm_nvmem_cell_release",
        "drivers/nvmem/core.c:nvmem_device_remove_all_cells",
        "drivers/hte/hte.c:hte_ts_put",
        "lib/kobject.c:kset_register",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790000,
      "name": "kfree_const",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964880,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:38",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:trace_array_create_systems",
        "kernel/trace/trace_events.c:event_subsystem_dir",
        "kernel/trace/trace_events.c:__put_system",
        "kernel/trace/trace_events_hist.c:destroy_hist_data",
        "kernel/trace/trace_events_hist.c:create_var_fields",
        "kernel/trace/trace_events_hist.c:create_var",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/char_dev.c:cdev_add",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:delayed_free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "fs/tracefs/event_inode.c:release_ei",
        "lib/genalloc.c:gen_pool_destroy",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodev_release",
        "drivers/acpi/scan.c:acpi_device_add",
        "drivers/acpi/scan.c:acpi_device_del_work_fn",
        "drivers/acpi/scan.c:acpi_device_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents",
        "drivers/regulator/core.c:_regulator_put",
        "drivers/regulator/core.c:create_regulator",
        "drivers/base/class.c:class_register",
        "drivers/base/power/wakeup.c:wakeup_source_register",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:regmap_reinit_cache",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/gpu/drm/drm_managed.c:drm_managed_release",
        "drivers/thermal/thermal_core.c:thermal_release",
        "drivers/leds/led-class.c:led_get",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/remoteproc/remoteproc_core.c:rproc_set_firmware",
        "drivers/nvmem/core.c:nvmem_cell_put",
        "drivers/nvmem/core.c:nvmem_device_remove_all_cells",
        "drivers/nvmem/core.c:nvmem_cell_attr_read",
        "drivers/hte/hte.c:hte_ts_put",
        "lib/kobject.c:kset_register",
        "lib/kobject.c:kobject_cleanup",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964880,
      "name": "kfree_const",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492613024,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/pinctrl/devicetree.c:dt_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_put",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492613024,
      "name": "kfree_const",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226464828,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/pinctrl/devicetree.c:dt_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/clk/clk.c:clk_core_free_parent_map",
        "drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/renesas/renesas-soc.c:renesas_soc_init",
        "drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked",
        "sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked",
        "sound/soc/soc-dapm.c:snd_soc_dapm_free_widget",
        "sound/soc/soc-dapm.c:snd_soc_dapm_free_widget",
        "lib/kobject.c:kobject_put",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226464828,
      "name": "kfree_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285930000,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "lib/genalloc.c:gen_pool_destroy",
        "drivers/pinctrl/devicetree.c:dt_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_put",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285930000,
      "name": "kfree_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272639568,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/pinctrl/devicetree.c:dt_free_map",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_put",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272639568,
      "name": "kfree_const",
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
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193312,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193312,
      "name": "kfree_const",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140064,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvme/host/core.c:nvme_init_ctrl",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140064,
      "name": "kfree_const",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184512,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184512,
      "name": "kfree_const",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void kfree_const(const void * x)
```

```json
{
  "name": "kfree_const",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247760,
      "name": "kfree_const",
      "external": true,
      "loc": "mm/util.c:37",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:event_create_dir",
        "mm/slab_common.c:slab_kmem_cache_release",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "fs/namespace.c:free_vfsmnt",
        "fs/namespace.c:alloc_vfsmnt",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_free_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiodevice_release",
        "drivers/acpi/scan.c:acpi_free_pnp_ids",
        "drivers/clk/clk.c:__clk_put",
        "drivers/clk/clk.c:clk_unregister",
        "drivers/clk/clk.c:__clk_release",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:__clk_register",
        "drivers/clk/clk.c:clk_hw_create_clk",
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop",
        "drivers/base/power/wakeup.c:wakeup_source_free",
        "drivers/base/power/wakeup.c:wakeup_source_create",
        "drivers/base/firmware_loader/main.c:device_uncache_fw_images_work",
        "drivers/base/firmware_loader/main.c:dev_cache_fw_image",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_nowait",
        "drivers/base/firmware_loader/main.c:request_firmware_work_func",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:fw_name_devm_release",
        "drivers/base/firmware_loader/main.c:__free_fw_priv",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/node.c:node_add_cache",
        "drivers/base/regmap/regmap.c:regmap_exit",
        "drivers/base/regmap/regmap.c:__regmap_init",
        "drivers/nvmem/core.c:nvmem_cell_drop",
        "lib/kobject.c:kobject_release",
        "lib/kobject.c:kobject_rename",
        "lib/kobject.c:kobject_set_name_vargs",
        "lib/kobject.c:kobject_set_name_vargs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247760,
      "name": "kfree_const",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
