# Function: <code>bpf_local_storage_lookup</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "bpf_local_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138128,
      "name": "bpf_local_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:205",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138128,
      "name": "bpf_local_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "bpf_local_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094544,
      "name": "bpf_local_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:208",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094544,
      "name": "bpf_local_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "bpf_local_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323824,
      "name": "bpf_local_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:208",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323824,
      "name": "bpf_local_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "bpf_local_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581627296,
      "name": "bpf_local_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:237",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_get",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581627296,
      "name": "bpf_local_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "bpf_local_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582014112,
      "name": "bpf_local_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:247",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014112,
      "name": "bpf_local_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "bpf_local_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205824,
      "name": "bpf_local_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:419",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205824,
      "name": "bpf_local_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
```

```json
{
  "name": "bpf_local_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582355088,
      "name": "bpf_local_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:419",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem",
        "kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_delete",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_get",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem",
        "net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582355088,
      "name": "bpf_local_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct bpf_local_storage_data * bpf_local_storage_lookup(struct bpf_local_storage * local_storage, struct bpf_local_storage_map * smap, bool cacheit_lockit)
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
