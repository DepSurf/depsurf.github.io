# Function: <code>bpf_local_storage_map_alloc</code>

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
struct bpf_local_storage_map * bpf_local_storage_map_alloc(union bpf_attr * attr)
```

```json
{
  "name": "bpf_local_storage_map_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139872,
      "name": "bpf_local_storage_map_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:543",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc",
        "kernel/bpf/bpf_task_storage.c:task_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139872,
      "name": "bpf_local_storage_map_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
struct bpf_local_storage_map * bpf_local_storage_map_alloc(union bpf_attr * attr)
```

```json
{
  "name": "bpf_local_storage_map_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096320,
      "name": "bpf_local_storage_map_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:558",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_alloc",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096320,
      "name": "bpf_local_storage_map_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_local_storage_map * bpf_local_storage_map_alloc(union bpf_attr * attr)
```

```json
{
  "name": "bpf_local_storage_map_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:558",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_alloc",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186667,
      "name": "bpf_local_storage_map_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581325696,
      "name": "bpf_local_storage_map_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_local_storage_map * bpf_local_storage_map_alloc(union bpf_attr * attr)
```

```json
{
  "name": "bpf_local_storage_map_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:607",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_alloc",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960991,
      "name": "bpf_local_storage_map_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581629648,
      "name": "bpf_local_storage_map_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_map * bpf_local_storage_map_alloc(union bpf_attr * attr, struct bpf_local_storage_cache * cache)
```

```json
{
  "name": "bpf_local_storage_map_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:640",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_alloc",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc",
        "kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596021588,
      "name": "bpf_local_storage_map_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582016336,
      "name": "bpf_local_storage_map_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_map * bpf_local_storage_map_alloc(union bpf_attr * attr, struct bpf_local_storage_cache * cache, bool bpf_ma)
```

```json
{
  "name": "bpf_local_storage_map_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:811",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_alloc",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc",
        "kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596543476,
      "name": "bpf_local_storage_map_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582208400,
      "name": "bpf_local_storage_map_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct bpf_map * bpf_local_storage_map_alloc(union bpf_attr * attr, struct bpf_local_storage_cache * cache, bool bpf_ma)
```

```json
{
  "name": "bpf_local_storage_map_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_alloc",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:792",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_alloc",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc",
        "kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_alloc",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597446569,
      "name": "bpf_local_storage_map_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582357488,
      "name": "bpf_local_storage_map_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
struct bpf_local_storage_map * bpf_local_storage_map_alloc(union bpf_attr * attr)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_local_storage_cache * cache</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct bpf_local_storage_map *</code> ➡️ <code>struct bpf_map *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool bpf_ma</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
