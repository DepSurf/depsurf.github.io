# Function: <code>do_migrate_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816448,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:988",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:SyS_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816448,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941872,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1020",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:SyS_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941872,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014352,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1022",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014352,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581056720,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:950",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055008,
      "name": "do_migrate_pages.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071581061744,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581167959,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1004",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:SYSC_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166368,
      "name": "do_migrate_pages.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
    },
    {
      "addr": 18446744071581172832,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581311757,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:980",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309680,
      "name": "do_migrate_pages.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071581317584,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581393309,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1020",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391616,
      "name": "do_migrate_pages.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071581401744,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581505506,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1058",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503840,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071581513888,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581569833,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1059",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568240,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071581578256,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581783197,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1128",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781552,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
    },
    {
      "addr": 18446744071581787840,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832784,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1110",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832784,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863632,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1120",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863632,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155168,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1091",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155168,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610352,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1087",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610352,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583133584,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1103",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583133584,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343904,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1109",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343904,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 782
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
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583580064,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1067",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583580064,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493006212,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1059",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493004168,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
    },
    {
      "addr": 18446603336493015760,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_pages",
      "external": false,
      "loc": "include/linux/mempolicy.h:285",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286434916,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1059",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286432912,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
    },
    {
      "addr": 13835058055286442384,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_pages",
      "external": false,
      "loc": "include/linux/mempolicy.h:285",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581538569,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1059",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536976,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071581546992,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581480329,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1059",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581478736,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071581488640,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581529881,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1059",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528288,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071581538304,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```

```json
{
  "name": "do_migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581596615,
      "name": "do_migrate_pages",
      "external": true,
      "loc": "mm/mempolicy.c:1059",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_migrate_pages"
      ],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn",
        "mm/mempolicy.c:kernel_migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581594976,
      "name": "do_migrate_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
    },
    {
      "addr": 18446744071581603344,
      "name": "do_migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_migrate_pages(struct mm_struct * mm, const nodemask_t * from, const nodemask_t * to, int flags)
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
