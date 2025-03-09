# Function: <code>rdtgroup_mkdir_ctrl_mon</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579123200,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1639",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579137456,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1721",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147033,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1821",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579212745,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2714",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579226435,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2782",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579228745,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579251296,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2881",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251296,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244256,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2913",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244256,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246048,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2909",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246048,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2968",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286384,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071592069992,
      "name": "rdtgroup_mkdir_ctrl_mon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2968",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579340416,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
    },
    {
      "addr": 18446744071593836189,
      "name": "rdtgroup_mkdir_ctrl_mon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3018",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408640,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
    },
    {
      "addr": 18446744071595963638,
      "name": "rdtgroup_mkdir_ctrl_mon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3305",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420976,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    },
    {
      "addr": 18446744071596481304,
      "name": "rdtgroup_mkdir_ctrl_mon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3440",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446384,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
    },
    {
      "addr": 18446744071597377350,
      "name": "rdtgroup_mkdir_ctrl_mon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227593,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579162521,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579228665,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_mkdir_ctrl_mon",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579234073,
      "name": "rdtgroup_mkdir_ctrl_mon",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2786",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int rdtgroup_mkdir_ctrl_mon(struct kernfs_node * parent_kn, const char * name, umode_t mode)
```
</details>
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
