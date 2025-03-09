# Function: <code>psi_trigger_create</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857104,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1006",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857104,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579905632,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905632,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579945584,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1056",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945584,
      "name": "psi_trigger_create.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
    },
    {
      "addr": 18446744071579950368,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579933744,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1072",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933744,
      "name": "psi_trigger_create.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
    },
    {
      "addr": 18446744071579938928,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579941168,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1108",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941168,
      "name": "psi_trigger_create.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071579946480,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071124,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1085",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066192,
      "name": "psi_trigger_create.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
    },
    {
      "addr": 18446744071592121353,
      "name": "psi_trigger_create.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580073712,
      "name": "psi_trigger_create",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1086",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593891231,
      "name": "psi_trigger_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580206912,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1255",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_write",
        "kernel/cgroup/cgroup.c:pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983435,
      "name": "psi_trigger_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580398720,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 722
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, enum psi_res res, struct file * file, struct kernfs_open_file * of)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1278",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_write",
        "kernel/cgroup/cgroup.c:pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501827,
      "name": "psi_trigger_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580467168,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 910
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, enum psi_res res, struct file * file, struct kernfs_open_file * of)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1270",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_write",
        "kernel/cgroup/cgroup.c:pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399513,
      "name": "psi_trigger_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071580526912,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 957
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491105640,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491105640,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225104300,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225104300,
      "name": "psi_trigger_create.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
    },
    {
      "addr": 3225110912,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283997712,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283997712,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271685058,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271685058,
      "name": "psi_trigger_create.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446743936271687896,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579877744,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877744,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579812736,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812736,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579865904,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865904,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
```

```json
{
  "name": "psi_trigger_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911280,
      "name": "psi_trigger_create",
      "external": true,
      "loc": "kernel/sched/psi.c:1007",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_pressure_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911280,
      "name": "psi_trigger_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
struct psi_trigger * psi_trigger_create(struct psi_group * group, char * buf, size_t nbytes, enum psi_res res)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t nbytes</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, buf, nbytes, res</code> ➡️ <code>group, buf, res</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param added. </b>
<code>struct kernfs_open_file * of</code>
</li>
</ul>
</details>
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
