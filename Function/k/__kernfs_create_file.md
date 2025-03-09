# Function: <code>__kernfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581515984,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:908",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515984,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701872,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:929",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701872,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789744,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:930",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789744,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581844704,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:976",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844704,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994512,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:976",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994512,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182128,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:978",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182128,
      "name": "__kernfs_create_file",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582277280,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:977",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277280,
      "name": "__kernfs_create_file",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441904,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441904,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540656,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540656,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582846832,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_add_file",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846832,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582919552,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:971",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_add_file",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919552,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947216,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:971",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947216,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282432,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:971",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282432,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583786912,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:973",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_bin_file_mode_ns",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583786912,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406128,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:1033",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_bin_file_mode_ns",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406128,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584634672,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:1033",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_bin_file_mode_ns",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634672,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584866784,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:1011",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_bin_file_mode_ns",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584866784,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494177440,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494177440,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227614992,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227614992,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287863616,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287863616,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273643366,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273643366,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582509392,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582509392,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582446560,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582446560,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582499872,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582499872,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct kernfs_node * __kernfs_create_file(struct kernfs_node * parent, const char * name, umode_t mode, kuid_t uid, kgid_t gid, loff_t size, const struct kernfs_ops * ops, void * priv, const void * ns, struct lock_class_key * key)
```

```json
{
  "name": "__kernfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580480,
      "name": "__kernfs_create_file",
      "external": true,
      "loc": "fs/kernfs/file.c:987",
      "file": "fs/kernfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "fs/sysfs/file.c:sysfs_add_file_mode_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580480,
      "name": "__kernfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
<code>parent, name, mode, size, ops, priv, ns, key</code> ➡️ <code>parent, name, mode, uid, gid, size, ops, priv, ns, key</code>
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
