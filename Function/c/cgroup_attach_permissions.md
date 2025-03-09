# Function: <code>cgroup_attach_permissions</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580385273,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4710",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580372248,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4711",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_threads_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write",
        "kernel/cgroup/cgroup.c:cgroup_procs_write"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cgroup_attach_permissions(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb, bool threadgroup)
```

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580339936,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4724",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339936,
      "name": "cgroup_attach_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
int cgroup_attach_permissions(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb, bool threadgroup, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580494800,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4896",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494800,
      "name": "cgroup_attach_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int cgroup_attach_permissions(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb, bool threadgroup, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580693584,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4907",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693584,
      "name": "cgroup_attach_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
int cgroup_attach_permissions(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb, bool threadgroup, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580964112,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5104",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580964112,
      "name": "cgroup_attach_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cgroup_attach_permissions(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb, bool threadgroup, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581052192,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5081",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052192,
      "name": "cgroup_attach_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cgroup_attach_permissions(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb, bool threadgroup, struct cgroup_namespace * ns)
```

```json
{
  "name": "cgroup_attach_permissions",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581149840,
      "name": "cgroup_attach_permissions",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5117",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149840,
      "name": "cgroup_attach_permissions",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int cgroup_attach_permissions(struct cgroup * src_cgrp, struct cgroup * dst_cgrp, struct super_block * sb, bool threadgroup)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_namespace * ns</code>
</li>
</ul>
</details>
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
