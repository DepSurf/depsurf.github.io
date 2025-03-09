# Function: <code>prefill_mem_cache</code>

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
void prefill_mem_cache(struct bpf_mem_cache * c, int cpu)
```

```json
{
  "name": "prefill_mem_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105376,
      "name": "prefill_mem_cache",
      "external": false,
      "loc": "kernel/bpf/memalloc.c:346",
      "file": "kernel/bpf/memalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105376,
      "name": "prefill_mem_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
void prefill_mem_cache(struct bpf_mem_cache * c, int cpu)
```

```json
{
  "name": "prefill_mem_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582300624,
      "name": "prefill_mem_cache",
      "external": false,
      "loc": "kernel/bpf/memalloc.c:349",
      "file": "kernel/bpf/memalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300624,
      "name": "prefill_mem_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
  "name": "prefill_mem_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582462472,
      "name": "prefill_mem_cache",
      "external": false,
      "loc": "kernel/bpf/memalloc.c:492",
      "file": "kernel/bpf/memalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void prefill_mem_cache(struct bpf_mem_cache * c, int cpu)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void prefill_mem_cache(struct bpf_mem_cache * c, int cpu)
```
</details>
</li>
</ul>
