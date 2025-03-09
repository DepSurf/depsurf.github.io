# Function: <code>bpf_map_alloc_percpu</code>

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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
```

```json
{
  "name": "bpf_map_alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580933072,
      "name": "bpf_map_alloc_percpu",
      "external": true,
      "loc": "kernel/bpf/syscall.c:428",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933072,
      "name": "bpf_map_alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
```

```json
{
  "name": "bpf_map_alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936080,
      "name": "bpf_map_alloc_percpu",
      "external": true,
      "loc": "kernel/bpf/syscall.c:429",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936080,
      "name": "bpf_map_alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
```

```json
{
  "name": "bpf_map_alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139920,
      "name": "bpf_map_alloc_percpu",
      "external": true,
      "loc": "kernel/bpf/syscall.c:448",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139920,
      "name": "bpf_map_alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
```

```json
{
  "name": "bpf_map_alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412704,
      "name": "bpf_map_alloc_percpu",
      "external": true,
      "loc": "kernel/bpf/syscall.c:455",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412704,
      "name": "bpf_map_alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
```

```json
{
  "name": "bpf_map_alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581765984,
      "name": "bpf_map_alloc_percpu",
      "external": true,
      "loc": "kernel/bpf/syscall.c:473",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581765984,
      "name": "bpf_map_alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
```

```json
{
  "name": "bpf_map_alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581927552,
      "name": "bpf_map_alloc_percpu",
      "external": true,
      "loc": "kernel/bpf/syscall.c:456",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581927552,
      "name": "bpf_map_alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
```

```json
{
  "name": "bpf_map_alloc_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053984,
      "name": "bpf_map_alloc_percpu",
      "external": true,
      "loc": "kernel/bpf/syscall.c:457",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "kernel/bpf/hashtab.c:prealloc_init",
        "kernel/bpf/arraymap.c:array_map_alloc",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053984,
      "name": "bpf_map_alloc_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void * bpf_map_alloc_percpu(const struct bpf_map * map, size_t size, size_t align, gfp_t flags)
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
