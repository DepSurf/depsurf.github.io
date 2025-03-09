# Function: <code>kernfs_remove_by_name_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511248,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1399",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511248,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696880,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1448",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696880,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784848,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1399",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784848,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581839632,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1409",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839632,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989376,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1474",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989376,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176944,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176944,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272080,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272080,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436464,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436464,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535200,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535200,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582841168,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1501",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582841168,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582913920,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1500",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913920,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582941616,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1502",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941616,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276784,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1529",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276784,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583780960,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1572",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780960,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584399536,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1644",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584399536,
      "name": "kernfs_remove_by_name_ns",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584628080,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1651",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584628080,
      "name": "kernfs_remove_by_name_ns",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584860240,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1667",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:create_files",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860240,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494169632,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494169632,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227609412,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:remove_files",
        "fs/sysfs/group.c:remove_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227609412,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287854048,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287854048,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273638200,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273638200,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503936,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503936,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441152,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441152,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494416,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494416,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int kernfs_remove_by_name_ns(struct kernfs_node * parent, const char * name, const void * ns)
```

```json
{
  "name": "kernfs_remove_by_name_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582575056,
      "name": "kernfs_remove_by_name_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1497",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_remove_bin_file",
        "fs/sysfs/file.c:sysfs_remove_file_from_group",
        "fs/sysfs/file.c:sysfs_remove_files",
        "fs/sysfs/file.c:sysfs_create_files",
        "fs/sysfs/dir.c:sysfs_remove_mount_point",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_remove_link",
        "fs/sysfs/symlink.c:sysfs_delete_link",
        "fs/sysfs/group.c:sysfs_remove_link_from_group",
        "fs/sysfs/group.c:sysfs_unmerge_group",
        "fs/sysfs/group.c:sysfs_merge_group",
        "fs/sysfs/group.c:internal_create_group",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582575056,
      "name": "kernfs_remove_by_name_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
