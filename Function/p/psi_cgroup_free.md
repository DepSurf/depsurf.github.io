# Function: <code>psi_cgroup_free</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826384,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:638",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826384,
      "name": "psi_cgroup_free",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856240,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:878",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856240,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904768,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904768,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949872,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:926",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949872,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938432,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:942",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938432,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945648,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:954",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945648,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:969",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592121727,
      "name": "psi_cgroup_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580072704,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:967",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593891211,
      "name": "psi_cgroup_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580205728,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:1096",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983366,
      "name": "psi_cgroup_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580397040,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:1119",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501758,
      "name": "psi_cgroup_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580465504,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:1111",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399444,
      "name": "psi_cgroup_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580525248,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491104584,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491104584,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225110352,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225110352,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283996464,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283996464,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271687328,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271687328,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876880,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876880,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811872,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811872,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865040,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865040,
      "name": "psi_cgroup_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void psi_cgroup_free(struct cgroup * cgroup)
```

```json
{
  "name": "psi_cgroup_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910416,
      "name": "psi_cgroup_free",
      "external": true,
      "loc": "kernel/sched/psi.c:879",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910416,
      "name": "psi_cgroup_free",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void psi_cgroup_free(struct cgroup * cgroup)
```
</details>
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
