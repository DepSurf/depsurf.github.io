# Function: <code>bpf_mem_alloc_init</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int bpf_mem_alloc_init(struct bpf_mem_alloc * ma, int size, bool percpu)
```

```json
{
  "name": "bpf_mem_alloc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582106096,
      "name": "bpf_mem_alloc_init",
      "external": true,
      "loc": "kernel/bpf/memalloc.c:377",
      "file": "kernel/bpf/memalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_global_ma_init",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582106096,
      "name": "bpf_mem_alloc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int bpf_mem_alloc_init(struct bpf_mem_alloc * ma, int size, bool percpu)
```

```json
{
  "name": "bpf_mem_alloc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301328,
      "name": "bpf_mem_alloc_init",
      "external": true,
      "loc": "kernel/bpf/memalloc.c:380",
      "file": "kernel/bpf/memalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_global_ma_init",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/cpumask.c:cpumask_kfunc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301328,
      "name": "bpf_mem_alloc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int bpf_mem_alloc_init(struct bpf_mem_alloc * ma, int size, bool percpu)
```

```json
{
  "name": "bpf_mem_alloc_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582461120,
      "name": "bpf_mem_alloc_init",
      "external": true,
      "loc": "kernel/bpf/memalloc.c:513",
      "file": "kernel/bpf/memalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_global_ma_init",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc",
        "kernel/bpf/cpumask.c:cpumask_kfunc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582461120,
      "name": "bpf_mem_alloc_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 954
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
int bpf_mem_alloc_init(struct bpf_mem_alloc * ma, int size, bool percpu)
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
