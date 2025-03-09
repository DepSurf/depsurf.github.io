# Function: <code>bpf_selem_unlink</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581139627,
      "name": "bpf_selem_unlink",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:194",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138080,
      "name": "bpf_selem_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_selem_unlink(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096036,
      "name": "bpf_selem_unlink",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:197",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094496,
      "name": "bpf_selem_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_selem_unlink(struct bpf_local_storage_elem * selem)
```

```json
{
  "name": "bpf_selem_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581325428,
      "name": "bpf_selem_unlink",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:197",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323776,
      "name": "bpf_selem_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void bpf_selem_unlink(struct bpf_local_storage_elem * selem, bool use_trace_rcu)
```

```json
{
  "name": "bpf_selem_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581629328,
      "name": "bpf_selem_unlink",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:226",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627248,
      "name": "bpf_selem_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void bpf_selem_unlink(struct bpf_local_storage_elem * selem, bool use_trace_rcu)
```

```json
{
  "name": "bpf_selem_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582016913,
      "name": "bpf_selem_unlink",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:235",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014048,
      "name": "bpf_selem_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void bpf_selem_unlink(struct bpf_local_storage_elem * selem, bool reuse_now)
```

```json
{
  "name": "bpf_selem_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582209217,
      "name": "bpf_selem_unlink",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:407",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205760,
      "name": "bpf_selem_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void bpf_selem_unlink(struct bpf_local_storage_elem * selem, bool reuse_now)
```

```json
{
  "name": "bpf_selem_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582358305,
      "name": "bpf_selem_unlink",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:407",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355024,
      "name": "bpf_selem_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem * selem)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool use_trace_rcu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reuse_now</code>
</li>
<li>
<b>Param removed. </b>
<code>bool use_trace_rcu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
