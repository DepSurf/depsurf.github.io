# Function: <code>psi_trigger_destroy</code>

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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852912,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1081",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852912,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901456,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901456,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945008,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1131",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945008,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933264,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1145",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933264,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579940720,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1179",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579940720,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
void psi_trigger_destroy(struct psi_trigger * t)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580067326,
      "name": "psi_trigger_destroy",
      "external": true,
      "loc": "kernel/sched/psi.c:1155",
      "file": "kernel/sched/psi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_fop_release"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_fop_release",
        "kernel/cgroup/cgroup.c:cgroup_pressure_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066832,
      "name": "psi_trigger_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    },
    {
      "addr": 18446744071592121384,
      "name": "psi_trigger_destroy.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580073744,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void psi_trigger_destroy(struct psi_trigger * t)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580151005,
      "name": "psi_trigger_destroy",
      "external": true,
      "loc": "kernel/sched/psi.c:1158",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:psi_fop_release"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_release",
        "kernel/cgroup/cgroup.c:cgroup_pressure_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150496,
      "name": "psi_trigger_destroy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
    },
    {
      "addr": 18446744071593880738,
      "name": "psi_trigger_destroy.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580208160,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void psi_trigger_destroy(struct psi_trigger * t)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_trigger_destroy",
      "external": true,
      "loc": "kernel/sched/psi.c:1332",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_release",
        "kernel/cgroup/cgroup.c:cgroup_pressure_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983460,
      "name": "psi_trigger_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580400048,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
void psi_trigger_destroy(struct psi_trigger * t)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_trigger_destroy",
      "external": true,
      "loc": "kernel/sched/psi.c:1380",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_release",
        "kernel/cgroup/cgroup.c:cgroup_pressure_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501852,
      "name": "psi_trigger_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580468688,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
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
void psi_trigger_destroy(struct psi_trigger * t)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_trigger_destroy",
      "external": true,
      "loc": "kernel/sched/psi.c:1372",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_fop_release",
        "kernel/cgroup/cgroup.c:cgroup_pressure_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399538,
      "name": "psi_trigger_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580528480,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491100576,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491100576,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225106240,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225106240,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283992000,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283992000,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271683202,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271683202,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873568,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873568,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579808576,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579808576,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861728,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861728,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void psi_trigger_destroy(struct kref * ref)
```

```json
{
  "name": "psi_trigger_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907104,
      "name": "psi_trigger_destroy",
      "external": false,
      "loc": "kernel/sched/psi.c:1082",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_trigger_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907104,
      "name": "psi_trigger_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void psi_trigger_destroy(struct kref * ref)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct psi_trigger * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kref * ref</code>
</li>
</ul>
</details>
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
