# Function: <code>cgroup_apply_control_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012880,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup.c:3240",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012880,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046464,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup.c:3249",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046464,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048224,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2764",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048224,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098096,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2899",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098096,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2917",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157312,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071580170853,
      "name": "cgroup_apply_control_enable.cold.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2962",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205056,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071580218741,
      "name": "cgroup_apply_control_enable.cold.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3102",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253136,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
    },
    {
      "addr": 18446744071580267658,
      "name": "cgroup_apply_control_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301376,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    },
    {
      "addr": 18446744071580315864,
      "name": "cgroup_apply_control_enable.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580371600,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3044",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371600,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580358480,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3040",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580358480,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580361600,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3053",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361600,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520048,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071592161080,
      "name": "cgroup_apply_control_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3119",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717648,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071593934109,
      "name": "cgroup_apply_control_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3224",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580991648,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071595999687,
      "name": "cgroup_apply_control_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3193",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581079216,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071596517821,
      "name": "cgroup_apply_control_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3202",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176736,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071597418043,
      "name": "cgroup_apply_control_enable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491552792,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491552792,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225516928,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225516928,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284524208,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284524208,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
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
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271967130,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271967130,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270176,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    },
    {
      "addr": 18446744071580284664,
      "name": "cgroup_apply_control_enable.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217680,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    },
    {
      "addr": 18446744071580232072,
      "name": "cgroup_apply_control_enable.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261424,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    },
    {
      "addr": 18446744071580275912,
      "name": "cgroup_apply_control_enable.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int cgroup_apply_control_enable(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_apply_control_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_apply_control_enable",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3103",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314784,
      "name": "cgroup_apply_control_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
    },
    {
      "addr": 18446744071580329724,
      "name": "cgroup_apply_control_enable.cold",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int cgroup_apply_control_enable(struct cgroup * cgrp)
```
</details>
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
