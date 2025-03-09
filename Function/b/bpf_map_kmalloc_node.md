# Function: <code>bpf_map_kmalloc_node</code>

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
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
```

```json
{
  "name": "bpf_map_kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932752,
      "name": "bpf_map_kmalloc_node",
      "external": true,
      "loc": "kernel/bpf/syscall.c:403",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932752,
      "name": "bpf_map_kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
```

```json
{
  "name": "bpf_map_kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935760,
      "name": "bpf_map_kmalloc_node",
      "external": true,
      "loc": "kernel/bpf/syscall.c:404",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935760,
      "name": "bpf_map_kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
```

```json
{
  "name": "bpf_map_kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139600,
      "name": "bpf_map_kmalloc_node",
      "external": true,
      "loc": "kernel/bpf/syscall.c:423",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139600,
      "name": "bpf_map_kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
```

```json
{
  "name": "bpf_map_kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412352,
      "name": "bpf_map_kmalloc_node",
      "external": true,
      "loc": "kernel/bpf/syscall.c:430",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "net/core/sock_map.c:sock_hash_update_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412352,
      "name": "bpf_map_kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
```

```json
{
  "name": "bpf_map_kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765392,
      "name": "bpf_map_kmalloc_node",
      "external": true,
      "loc": "kernel/bpf/syscall.c:444",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765392,
      "name": "bpf_map_kmalloc_node",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
```

```json
{
  "name": "bpf_map_kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581926624,
      "name": "bpf_map_kmalloc_node",
      "external": true,
      "loc": "kernel/bpf/syscall.c:412",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926624,
      "name": "bpf_map_kmalloc_node",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
```

```json
{
  "name": "bpf_map_kmalloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053056,
      "name": "bpf_map_kmalloc_node",
      "external": true,
      "loc": "kernel/bpf/syscall.c:413",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/lpm_trie.c:trie_update_elem",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053056,
      "name": "bpf_map_kmalloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
void * bpf_map_kmalloc_node(const struct bpf_map * map, size_t size, gfp_t flags, int node)
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
