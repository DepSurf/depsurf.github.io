# Function: <code>rdtgroup_kn_set_ugid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121024,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:96",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121024,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579115408,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:104",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115408,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579128928,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:130",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128928,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579138256,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:130",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138256,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201024,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:195",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201024,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213808,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213808,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216096,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216096,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236592,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236592,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229392,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229392,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231472,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231472,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270256,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:192",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270256,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323024,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:192",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323024,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388976,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:192",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388976,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398496,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:205",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398496,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579425824,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:210",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579425824,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579214944,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579214944,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579149536,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149536,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216016,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216016,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_kn_set_ugid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221328,
      "name": "rdtgroup_kn_set_ugid",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:189",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221328,
      "name": "rdtgroup_kn_set_ugid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rdtgroup_kn_set_ugid(struct kernfs_node * kn)
```
</details>
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
