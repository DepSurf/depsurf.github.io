# Function: <code>kernfs_break_active_protection</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581510880,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1273",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rename",
        "kernel/cgroup.c:cgroup_rename",
        "kernel/cgroup.c:cgroup_kn_lock_live",
        "kernel/cpuset.c:cpuset_write_resmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510880,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581696592,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1322",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_rename",
        "kernel/cgroup.c:cgroup_rename",
        "kernel/cgroup.c:cgroup_kn_lock_live",
        "kernel/cpuset.c:cpuset_write_resmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696512,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581784560,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1273",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup.c:cgroup_rename",
        "kernel/cgroup.c:cgroup_rename",
        "kernel/cgroup.c:cgroup_kn_lock_live",
        "kernel/cpuset.c:cpuset_write_resmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784480,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581839344,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1283",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839264,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581989088,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1348",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989008,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582176656,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176576,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582271792,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271712,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582436174,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436096,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582534910,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534832,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582840878,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1375",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582840736,
      "name": "kernfs_break_active_protection",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582913630,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1374",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913488,
      "name": "kernfs_break_active_protection",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582941326,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1376",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941184,
      "name": "kernfs_break_active_protection",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583276494,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1403",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276352,
      "name": "kernfs_break_active_protection",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583780669,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1445",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780480,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584399229,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1514",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584399008,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584627773,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1521",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627552,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584859933,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1537",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859712,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494169300,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494169112,
      "name": "kernfs_break_active_protection",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227609012,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227608872,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287853632,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287853488,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273637864,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273637708,
      "name": "kernfs_break_active_protection",
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582503646,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503568,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582440862,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440784,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582494126,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494048,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void kernfs_break_active_protection(struct kernfs_node * kn)
```

```json
{
  "name": "kernfs_break_active_protection",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582574766,
      "name": "kernfs_break_active_protection",
      "external": true,
      "loc": "fs/kernfs/dir.c:1371",
      "file": "fs/kernfs/dir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cgroup-v1.c:cgroup1_rename",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "fs/sysfs/file.c:sysfs_break_active_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574688,
      "name": "kernfs_break_active_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
