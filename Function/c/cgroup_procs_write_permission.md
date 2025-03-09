# Function: <code>cgroup_procs_write_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579987997,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup.c:2778",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:__cgroup_procs_write"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580017635,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup.c:2836",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580051315,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup.c:2845",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580054543,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:2418",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083488,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4318",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083488,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138560,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4355",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138560,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185664,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4424",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185664,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580231344,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4714",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231344,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580279552,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580279552,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580349552,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4679",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580349552,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336000,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4680",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336000,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580339975,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4693",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580494830,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4865",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580693611,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4876",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580964152,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5073",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581052232,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5050",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581149880,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5086",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491526896,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491526896,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225493448,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225493448,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284493120,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284493120,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271946638,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271946638,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248352,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248352,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195904,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195904,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239600,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239600,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
```

```json
{
  "name": "cgroup_procs_write_permission",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580292592,
      "name": "cgroup_procs_write_permission",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4729",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580292592,
      "name": "cgroup_procs_write_permission",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int cgroup_procs_write_permission(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb)
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
