# Function: <code>kernfs_free_fs_context</code>

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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582426768,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426768,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525552,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525552,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582830480,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:356",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830480,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903264,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:356",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903264,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582931200,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:356",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582931200,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266000,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:356",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266000,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768880,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:358",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768880,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386192,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:363",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386192,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584614496,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:363",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584614496,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846576,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:372",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846576,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494157088,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494157088,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227598072,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227598072,
      "name": "kernfs_free_fs_context",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287836864,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287836864,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273628224,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273628224,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494288,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494288,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431520,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431520,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484768,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484768,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void kernfs_free_fs_context(struct fs_context * fc)
```

```json
{
  "name": "kernfs_free_fs_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565328,
      "name": "kernfs_free_fs_context",
      "external": true,
      "loc": "fs/kernfs/mount.c:333",
      "file": "fs/kernfs/mount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_fs_context_free",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "fs/sysfs/mount.c:sysfs_fs_context_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565328,
      "name": "kernfs_free_fs_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void kernfs_free_fs_context(struct fs_context * fc)
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
