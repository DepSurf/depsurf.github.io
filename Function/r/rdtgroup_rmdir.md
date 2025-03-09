# Function: <code>rdtgroup_rmdir</code>

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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579125344,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:990",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125344,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121824,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1809",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121824,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579135920,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1895",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579135920,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145568,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1996",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145568,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211184,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2901",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211184,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2969",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224896,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
    },
    {
      "addr": 18446744071579227386,
      "name": "rdtgroup_rmdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227168,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227168,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250336,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3066",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250336,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 385
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243312,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3085",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243312,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244640,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3081",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244640,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3140",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284800,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 978
    },
    {
      "addr": 18446744071592069941,
      "name": "rdtgroup_rmdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3140",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338832,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071593836138,
      "name": "rdtgroup_rmdir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407632,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3190",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407632,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419680,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3477",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419680,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444992,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3612",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444992,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226016,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226016,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579160944,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160944,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227088,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227088,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```

```json
{
  "name": "rdtgroup_rmdir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579232496,
      "name": "rdtgroup_rmdir",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2973",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232496,
      "name": "rdtgroup_rmdir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
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
int rdtgroup_rmdir(struct kernfs_node * kn)
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
int rdtgroup_rmdir(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int rdtgroup_rmdir(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int rdtgroup_rmdir(struct kernfs_node * kn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rdtgroup_rmdir(struct kernfs_node * kn)
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
