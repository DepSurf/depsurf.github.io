# Function: <code>kset_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956096,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:829",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956096,
      "name": "kset_unregister",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243792,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:829",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243792,
      "name": "kset_unregister",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583359104,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:829",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359104,
      "name": "kset_unregister",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588209376,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:832",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588209376,
      "name": "kset_unregister",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588758896,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:832",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "fs/ext4/sysfs.c:ext4_exit_sysfs",
        "fs/ext4/sysfs.c:ext4_init_sysfs",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758896,
      "name": "kset_unregister",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589137120,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:845",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137120,
      "name": "kset_unregister",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589372160,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:845",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589372160,
      "name": "kset_unregister",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589828944,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589828944,
      "name": "kset_unregister",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590055088,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055088,
      "name": "kset_unregister",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050352,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:893",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050352,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585200144,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:890",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585200144,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083216,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:890",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083216,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530144,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:890",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530144,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586684000,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:858",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684000,
      "name": "kset_unregister",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595764848,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:873",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595764848,
      "name": "kset_unregister",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596289248,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:874",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596289248,
      "name": "kset_unregister",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597174112,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:886",
      "file": "lib/kobject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597174112,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503831880,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503831880,
      "name": "kset_unregister",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236451216,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236451216,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297679232,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297679232,
      "name": "kset_unregister",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279724696,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279724696,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589657344,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589657344,
      "name": "kset_unregister",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589383168,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/hv/vmbus_drv.c:vmbus_device_unregister",
        "drivers/hv/vmbus_drv.c:vmbus_device_register",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383168,
      "name": "kset_unregister",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590100720,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590100720,
      "name": "kset_unregister",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void kset_unregister(struct kset * k)
```

```json
{
  "name": "kset_unregister",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590150960,
      "name": "kset_unregister",
      "external": true,
      "loc": "lib/kobject.c:876",
      "file": "lib/kobject.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:sysfs_slab_remove_workfn",
        "drivers/base/core.c:devices_init",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_unregister",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/bus.c:bus_register",
        "drivers/base/class.c:class_unregister",
        "drivers/base/swnode.c:software_node_exit",
        "drivers/firmware/edd.c:edd_exit",
        "drivers/firmware/edd.c:edd_init",
        "drivers/firmware/efi/efivars.c:efivars_sysfs_exit",
        "drivers/firmware/efi/esrt.c:esrt_sysfs_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "drivers/firmware/efi/runtime-map.c:efi_runtime_map_init",
        "net/core/net-sysfs.c:netdev_register_kobject",
        "net/core/net-sysfs.c:netdev_unregister_kobject"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590150960,
      "name": "kset_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
