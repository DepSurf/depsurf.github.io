# Function: <code>cgroup_control</code>

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
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580019065,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup.c:371",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup.c:cgroup_controllers_show"
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
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580052745,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup.c:374",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup.c:cgroup_controllers_show"
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
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580056919,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:329",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580076832,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:408",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076832,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135856,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:411",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135856,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183072,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:416",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183072,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580228464,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228464,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276672,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276672,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580344832,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:411",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344832,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580331056,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:408",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331056,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580334192,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:408",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334192,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580488816,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:432",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488816,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580716912,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:433",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
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
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580991493,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:438",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
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
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581079061,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:437",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
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
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581176587,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:439",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491523496,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491523496,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225490108,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:css_visible",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225490108,
      "name": "cgroup_control",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284488144,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284488144,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271942976,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271942976,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580245472,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245472,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580193024,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193024,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580236720,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236720,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289712,
      "name": "cgroup_control",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_propagate_control",
        "kernel/cgroup/cgroup.c:cgroup_controllers_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289712,
      "name": "cgroup_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
u16 cgroup_control(struct cgroup * cgrp)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
u16 cgroup_control(struct cgroup * cgrp)
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
