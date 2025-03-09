# Function: <code>kernfs_create_dir_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510304,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:917",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510304,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695936,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:965",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695936,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581783904,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:915",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783904,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581838608,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:925",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581838608,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581988336,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:992",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988336,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175920,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1012",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175920,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271056,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1012",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271056,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435440,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435440,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534176,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534176,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582840032,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1017",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840032,
      "name": "kernfs_create_dir_ns",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912784,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1016",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912784,
      "name": "kernfs_create_dir_ns",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940480,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1016",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940480,
      "name": "kernfs_create_dir_ns",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275616,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:975",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275616,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779504,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1001",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779504,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397760,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1023",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397760,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584626256,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1027",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626256,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584858512,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1043",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584858512,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494168272,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494168272,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227608188,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227608188,
      "name": "kernfs_create_dir_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287852384,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287852384,
      "name": "kernfs_create_dir_ns",
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273637032,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273637032,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502912,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502912,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440128,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440128,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582493392,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582493392,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct kernfs_node * kernfs_create_dir_ns(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, void * priv, const void * ns)
```

```json
{
  "name": "kernfs_create_dir_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582574032,
      "name": "kernfs_create_dir_ns",
      "external": true,
      "loc": "fs/kernfs/dir.c:1013",
      "file": "fs/kernfs/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "fs/sysfs/dir.c:sysfs_create_dir_ns",
        "fs/sysfs/group.c:internal_create_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574032,
      "name": "kernfs_create_dir_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>kuid_t uid</code>
</li>
<li>
<b>Param added. </b>
<code>kgid_t gid</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, name, mode, priv, ns</code> ➡️ <code>parent, name, mode, uid, gid, priv, ns</code>
</li>
</ul>
</details>
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
