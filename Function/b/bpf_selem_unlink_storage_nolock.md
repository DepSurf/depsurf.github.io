# Function: <code>bpf_selem_unlink_storage_nolock</code>

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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem)
```

```json
{
  "name": "bpf_selem_unlink_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581137296,
      "name": "bpf_selem_unlink_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:88",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137296,
      "name": "bpf_selem_unlink_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem)
```

```json
{
  "name": "bpf_selem_unlink_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093680,
      "name": "bpf_selem_unlink_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:88",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093680,
      "name": "bpf_selem_unlink_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem)
```

```json
{
  "name": "bpf_selem_unlink_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322864,
      "name": "bpf_selem_unlink_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:88",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322864,
      "name": "bpf_selem_unlink_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem, bool use_trace_rcu)
```

```json
{
  "name": "bpf_selem_unlink_storage_nolock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626128,
      "name": "bpf_selem_unlink_storage_nolock",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:107",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage",
        "kernel/bpf/bpf_task_storage.c:bpf_task_storage_free",
        "kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626128,
      "name": "bpf_selem_unlink_storage_nolock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem, bool use_trace_rcu)
```

```json
{
  "name": "bpf_selem_unlink_storage_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012352,
      "name": "bpf_selem_unlink_storage_nolock",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:116",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_unlink_nolock",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012352,
      "name": "bpf_selem_unlink_storage_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem, bool reuse_now)
```

```json
{
  "name": "bpf_selem_unlink_storage_nolock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204704,
      "name": "bpf_selem_unlink_storage_nolock",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:253",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204704,
      "name": "bpf_selem_unlink_storage_nolock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_selem_unlink_storage_nolock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582353936,
      "name": "bpf_selem_unlink_storage_nolock",
      "external": false,
      "loc": "kernel/bpf/bpf_local_storage.c:253",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_update",
        "kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353936,
      "name": "bpf_selem_unlink_storage_nolock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool bpf_selem_unlink_storage_nolock(struct bpf_local_storage * local_storage, struct bpf_local_storage_elem * selem, bool uncharge_mem, bool reuse_now)
```
</details>
</li>
</ul>
