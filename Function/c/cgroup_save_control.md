# Function: <code>cgroup_save_control</code>

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
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580019313,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup.c:3165",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write"
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
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580052993,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup.c:3174",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write"
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
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053752,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2689",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098832,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2824",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098832,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157248,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2842",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157248,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204976,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2884",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204976,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580253056,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3024",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253056,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580301296,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301296,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580352144,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2966",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352144,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580338160,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2962",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_enable_threaded",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338160,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580340944,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2975",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580340944,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497968,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3030",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497968,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580695280,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3041",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695280,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580965968,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3146",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965968,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054352,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3115",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054352,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152192,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3124",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152192,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491552704,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491552704,
      "name": "cgroup_save_control",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225516848,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225516848,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284524080,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284524080,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271967058,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271967058,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270096,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270096,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217600,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217600,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580261344,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261344,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void cgroup_save_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_save_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314704,
      "name": "cgroup_save_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:3025",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314704,
      "name": "cgroup_save_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void cgroup_save_control(struct cgroup * cgrp)
```
</details>
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
