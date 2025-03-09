# Function: <code>kernfs_get_tree</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582426240,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426240,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525024,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525024,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830176,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:315",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830176,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902960,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:315",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902960,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930672,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:315",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930672,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265472,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:315",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265472,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768368,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:316",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/sysfs/mount.c:sysfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768368,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584385664,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:321",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "fs/sysfs/mount.c:sysfs_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385664,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613936,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:321",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613936,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845952,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:328",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845952,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494156552,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494156552,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227597520,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227597520,
      "name": "kernfs_get_tree",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287836176,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287836176,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273627694,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273627694,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582493760,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582493760,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430992,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430992,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484240,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484240,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int kernfs_get_tree(struct fs_context * fc)
```

```json
{
  "name": "kernfs_get_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582564800,
      "name": "kernfs_get_tree",
      "external": true,
      "loc": "fs/kernfs/mount.c:292",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564800,
      "name": "kernfs_get_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int kernfs_get_tree(struct fs_context * fc)
```
</details>
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
