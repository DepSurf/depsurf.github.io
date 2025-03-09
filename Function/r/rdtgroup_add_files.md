# Function: <code>rdtgroup_add_files</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579121360,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:128",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121360,
      "name": "rdtgroup_add_files.constprop.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579115552,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:794",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115552,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129072,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:858",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129072,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:859",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579138400,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071579147856,
      "name": "rdtgroup_add_files.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1488",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201168,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071579214288,
      "name": "rdtgroup_add_files.cold.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1486",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213936,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579227264,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216224,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579229552,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1575",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236720,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579252416,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1608",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_setup_root",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229520,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071591257294,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1608",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231600,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071591200640,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1568",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270384,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071592068810,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1568",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323184,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071593835031,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389152,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1573",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389152,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579398672,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1845",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579398672,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1933",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579428880,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071597376226,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215072,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579228400,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579149664,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579163328,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216144,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579229472,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```

```json
{
  "name": "rdtgroup_add_files",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_add_files",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1484",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221456,
      "name": "rdtgroup_add_files",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071579234880,
      "name": "rdtgroup_add_files.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```
</details>
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
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rdtgroup_add_files(struct kernfs_node * kn, long unsigned int fflags)
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
