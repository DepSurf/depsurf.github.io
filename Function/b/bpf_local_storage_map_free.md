# Function: <code>bpf_local_storage_map_free</code>

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
void bpf_local_storage_map_free(struct bpf_local_storage_map * smap)
```

```json
{
  "name": "bpf_local_storage_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139552,
      "name": "bpf_local_storage_map_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:471",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139552,
      "name": "bpf_local_storage_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void bpf_local_storage_map_free(struct bpf_local_storage_map * smap, int * busy_counter)
```

```json
{
  "name": "bpf_local_storage_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095968,
      "name": "bpf_local_storage_map_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:477",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095968,
      "name": "bpf_local_storage_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void bpf_local_storage_map_free(struct bpf_local_storage_map * smap, int * busy_counter)
```

```json
{
  "name": "bpf_local_storage_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:477",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592186637,
      "name": "bpf_local_storage_map_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581325328,
      "name": "bpf_local_storage_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
void bpf_local_storage_map_free(struct bpf_local_storage_map * smap, int * busy_counter)
```

```json
{
  "name": "bpf_local_storage_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:526",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593960961,
      "name": "bpf_local_storage_map_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581629232,
      "name": "bpf_local_storage_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bpf_local_storage_map_free(struct bpf_map * map, struct bpf_local_storage_cache * cache, int * busy_counter)
```

```json
{
  "name": "bpf_local_storage_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:653",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596021618,
      "name": "bpf_local_storage_map_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582016784,
      "name": "bpf_local_storage_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void bpf_local_storage_map_free(struct bpf_map * map, struct bpf_local_storage_cache * cache, int * busy_counter)
```

```json
{
  "name": "bpf_local_storage_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:867",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596543506,
      "name": "bpf_local_storage_map_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071582209072,
      "name": "bpf_local_storage_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void bpf_local_storage_map_free(struct bpf_map * map, struct bpf_local_storage_cache * cache, int * busy_counter)
```

```json
{
  "name": "bpf_local_storage_map_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_local_storage_map_free",
      "external": true,
      "loc": "kernel/bpf/bpf_local_storage.c:848",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_task_storage.c:task_storage_map_free",
        "kernel/bpf/bpf_inode_storage.c:inode_storage_map_free",
        "kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_free",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597446599,
      "name": "bpf_local_storage_map_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071582358160,
      "name": "bpf_local_storage_map_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void bpf_local_storage_map_free(struct bpf_local_storage_map * smap)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * busy_counter</code>
</li>
</ul>
</details>
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
<code>struct bpf_map * map</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_local_storage_cache * cache</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_local_storage_map * smap</code>
</li>
<li>
<b>Param reordered. </b>
<code>smap, busy_counter</code> ➡️ <code>map, cache, busy_counter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
