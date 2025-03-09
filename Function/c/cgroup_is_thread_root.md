# Function: <code>cgroup_is_thread_root</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082651,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:368",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082384,
      "name": "cgroup_is_thread_root.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580088608,
      "name": "cgroup_is_thread_root",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580147200,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:371",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147200,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580194800,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:376",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194800,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580241456,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241456,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580289632,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289632,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580356584,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:371",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580361168,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580343193,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:368",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347936,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580346409,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:368",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351056,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580502554,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:392",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507840,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580701829,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:393",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704144,
      "name": "cgroup_is_thread_root",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580974133,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:398",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977152,
      "name": "cgroup_is_thread_root",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581062085,
      "name": "cgroup_is_thread_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:397",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain"
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
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581159253,
      "name": "cgroup_is_thread_root",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:399",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain",
        "kernel/cgroup/cgroup.c:cgroup_is_valid_domain"
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491539304,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491539304,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225504536,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225504536,
      "name": "cgroup_is_thread_root",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284508208,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284508208,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271955510,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271955510,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580258432,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258432,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580205968,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205968,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580249680,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249680,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
```

```json
{
  "name": "cgroup_is_thread_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302864,
      "name": "cgroup_is_thread_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:378",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_type_show",
        "kernel/cgroup/cgroup.c:cgroup_subtree_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580302864,
      "name": "cgroup_is_thread_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool cgroup_is_thread_root(struct cgroup * cgrp)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool cgroup_is_thread_root(struct cgroup * cgrp)
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
