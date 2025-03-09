# Function: <code>cgroup_propagate_frozen</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580398752,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398752,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580386112,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580386112,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389040,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389040,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
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
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580551136,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580551136,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580749632,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580749632,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027008,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027008,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581115360,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115360,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213600,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213600,
      "name": "cgroup_propagate_frozen",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271993648,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_propagate_frozen",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup_propagate_frozen",
      "external": false,
      "loc": "kernel/cgroup/freezer.c:14",
      "file": "kernel/cgroup/freezer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_update_frozen"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cgroup_propagate_frozen(struct cgroup * cgrp, bool frozen)
```
</details>
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
