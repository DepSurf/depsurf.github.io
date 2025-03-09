# Function: <code>cgroup_finalize_control</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580019403,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup.c:3360",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:rebind_subsystems"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053083,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup.c:3369",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:rebind_subsystems"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053844,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2884",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
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
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580105239,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3019",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
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
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580164366,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3037",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580208049,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3082",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207552,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580256188,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3222",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580255680,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580304410,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303920,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580374110,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3164",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373264,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580360974,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3160",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360128,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580363766,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3173",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580363232,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580523432,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3228",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521904,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580725662,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3239",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581001166,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3340",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581089742,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3309",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581187246,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3318",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491556100,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491555584,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225520140,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225519608,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284528852,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284528144,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271970124,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271969670,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580273210,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272720,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580220714,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220224,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580264458,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263968,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```

```json
{
  "name": "cgroup_finalize_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580317802,
      "name": "cgroup_finalize_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3223",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317312,
      "name": "cgroup_finalize_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void cgroup_finalize_control(struct cgroup * cgrp, int ret)
```
</details>
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
