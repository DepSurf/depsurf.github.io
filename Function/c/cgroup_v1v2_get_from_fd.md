# Function: <code>cgroup_v1v2_get_from_fd</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cgroup * cgroup_v1v2_get_from_fd(int fd)
```

```json
{
  "name": "cgroup_v1v2_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581010549,
      "name": "cgroup_v1v2_get_from_fd",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6856",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd"
      ],
      "caller_func": [
        "kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010816,
      "name": "cgroup_v1v2_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct cgroup * cgroup_v1v2_get_from_fd(int fd)
```

```json
{
  "name": "cgroup_v1v2_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099200,
      "name": "cgroup_v1v2_get_from_fd",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6839",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099200,
      "name": "cgroup_v1v2_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
struct cgroup * cgroup_v1v2_get_from_fd(int fd)
```

```json
{
  "name": "cgroup_v1v2_get_from_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196624,
      "name": "cgroup_v1v2_get_from_fd",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:6880",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196624,
      "name": "cgroup_v1v2_get_from_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct cgroup * cgroup_v1v2_get_from_fd(int fd)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
