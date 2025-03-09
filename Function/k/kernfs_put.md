# Function: <code>kernfs_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581505728,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:546",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "fs/kernfs/mount.c:kernfs_kill_sb",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dop_release",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "lib/kobject.c:kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:md_free",
        "drivers/md/bitmap.c:bitmap_destroy",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505728,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581691168,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:545",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup.c:css_free_work_fn",
        "fs/kernfs/mount.c:kernfs_kill_sb",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_dop_release",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691168,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581779248,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:495",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock",
        "kernel/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup.c:css_free_work_fn",
        "fs/kernfs/mount.c:kernfs_kill_sb",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:__kernfs_remove",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_dop_release",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581779248,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581833984,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:505",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "fs/kernfs/mount.c:kernfs_kill_sb",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_dop_release",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833984,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581983744,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983744,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582172208,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172208,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582266784,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582266784,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582431280,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:505",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431280,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582530048,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530048,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582837303,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:__kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836272,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071582836672,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582910055,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:__kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909024,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071582909424,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582937495,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:__kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582936272,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071582936672,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583272263,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:508",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:__kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271024,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071592248789,
      "name": "kernfs_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583271440,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583776295,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:516",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "lib/kobject.c:__kobject_del",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774912,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071594029840,
      "name": "kernfs_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583775344,
      "name": "kernfs_put",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584394247,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:537",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "lib/kobject.c:__kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584393040,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071596063739,
      "name": "kernfs_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584393440,
      "name": "kernfs_put",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584622679,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:534",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/mount.c:__kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "lib/kobject.c:__kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621440,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071596587657,
      "name": "kernfs_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584621808,
      "name": "kernfs_put",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584855175,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:538",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_parent",
        "fs/kernfs/mount.c:kernfs_fh_to_dentry",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_remove_by_name_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_destroy_root",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:sysfs_remove_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/usb/core/port.c:usb_hub_remove_port_device",
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/md.c:md_kobj_release",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:md_kick_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/leds/led-class.c:led_classdev_unregister",
        "lib/kobject.c:__kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584853984,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071597493485,
      "name": "kernfs_put.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071584854368,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494161912,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/of/kobj.c:safe_name",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494161912,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227602404,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/symlink.c:sysfs_do_create_link_sd",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/of/kobj.c:safe_name",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227602404,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287843440,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init",
        "drivers/of/kobj.c:safe_name",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287843440,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273632966,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "drivers/of/kobj.c:safe_name",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273632314,
      "name": "kernfs_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446743936273632770,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582498784,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498784,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582436016,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/nfit/core.c:acpi_nfit_register_dimms",
        "drivers/acpi/nfit/core.c:shutdown_dimm_notify",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/nvdimm/pmem.c:nd_pmem_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436016,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582489264,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489264,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void kernfs_put(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582569440,
      "name": "kernfs_put",
      "external": true,
      "loc": "fs/kernfs/dir.c:506",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict",
        "kernel/cgroup/cgroup.c:cgroup_get_from_path",
        "kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "fs/kernfs/mount.c:kernfs_fh_get_inode",
        "fs/kernfs/mount.c:kernfs_get_node_by_id",
        "fs/kernfs/inode.c:kernfs_evict_inode",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_pos",
        "fs/kernfs/dir.c:kernfs_dir_fop_release",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_create_empty_dir",
        "fs/kernfs/dir.c:kernfs_create_dir_ns",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/file.c:__kernfs_create_file",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/file.c:kernfs_notify_workfn",
        "fs/kernfs/symlink.c:kernfs_create_link",
        "fs/sysfs/file.c:sysfs_file_change_owner",
        "fs/sysfs/file.c:sysfs_link_change_owner",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_file_self",
        "fs/sysfs/file.c:sysfs_unbreak_active_protection",
        "fs/sysfs/file.c:sysfs_chmod_file",
        "fs/sysfs/file.c:sysfs_add_file_to_group",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/file.c:sysfs_notify",
        "fs/sysfs/dir.c:sysfs_rename_dir_ns",
        "fs/sysfs/symlink.c:sysfs_rename_link_ns",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:sysfs_group_change_owner",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_add_link_to_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/nvdimm/dimm_devs.c:shutdown_security_notify",
        "drivers/nvdimm/region.c:nd_region_remove",
        "drivers/md/md.c:md_free",
        "drivers/md/md.c:unbind_rdev_from_array",
        "drivers/md/md.c:mddev_unlock",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_free",
        "lib/kobject.c:kobject_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569440,
      "name": "kernfs_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
