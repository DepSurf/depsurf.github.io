# Function: <code>cgroup_bpf_query</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111552,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5865",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111552,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170720,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:5903",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170720,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218608,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6006",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218608,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267424,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6430",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267424,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580315744,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315744,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387216,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6521",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387216,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374352,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6513",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374352,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580377280,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6491",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580377280,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538496,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6714",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538496,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749670,
      "name": "cgroup_bpf_query",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:906",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
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
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582164678,
      "name": "cgroup_bpf_query",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1118",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
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
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582361606,
      "name": "cgroup_bpf_query",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1118",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
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
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582528502,
      "name": "cgroup_bpf_query",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1119",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491569032,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491569032,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225533968,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225533968,
      "name": "cgroup_bpf_query",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284548928,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284548928,
      "name": "cgroup_bpf_query",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271982418,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271982418,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284544,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284544,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231952,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231952,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275792,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275792,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
```

```json
{
  "name": "cgroup_bpf_query",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329600,
      "name": "cgroup_bpf_query",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6449",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329600,
      "name": "cgroup_bpf_query",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
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
int cgroup_bpf_query(struct cgroup * cgrp, const union bpf_attr * attr, union bpf_attr * uattr)
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
