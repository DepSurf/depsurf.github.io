# Function: <code>kernfs_find_and_get_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581507200,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:837",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:md_run",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507200,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692624,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:862",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692624,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780704,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:812",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780704,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835376,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:822",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835376,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581985168,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:888",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985168,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171088,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:905",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171088,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582266528,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:905",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266528,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431024,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:of_led_classdev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431024,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582529792,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529792,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582835008,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:900",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835008,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907760,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:899",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907760,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935328,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:899",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935328,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270480,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:858",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270480,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583774784,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:866",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774784,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584392896,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:885",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392896,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584621296,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:887",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621296,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584853840,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:903",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584853840,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494162888,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/of/kobj.c:safe_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494162888,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227605248,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/of/kobj.c:safe_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227605248,
      "name": "kernfs_find_and_get_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287848336,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/of/kobj.c:safe_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287848336,
      "name": "kernfs_find_and_get_ns",
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273632038,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext",
        "drivers/of/kobj.c:safe_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273632038,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582498528,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498528,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435760,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_dimms",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_dimms",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435760,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489008,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489008,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct kernfs_node * kernfs_find_and_get_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_find_and_get_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571744,
      "name": "kernfs_find_and_get_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:906",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_break_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_probe",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/leds/led-class.c:led_classdev_register_ext"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571744,
      "name": "kernfs_find_and_get_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
