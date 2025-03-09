# Function: <code>__bpf_map_area_alloc</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923168,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:266",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923168,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919392,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:274",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919392,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923328,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:275",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923328,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125984,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:294",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125984,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397296,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:300",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397296,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747648,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:300",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747648,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581907616,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:273",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581907616,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```

```json
{
  "name": "__bpf_map_area_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031856,
      "name": "__bpf_map_area_alloc",
      "external": false,
      "loc": "kernel/bpf/syscall.c:274",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_area_mmapable_alloc",
        "kernel/bpf/syscall.c:bpf_map_area_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031856,
      "name": "__bpf_map_area_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * __bpf_map_area_alloc(u64 size, int numa_node, bool mmapable)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
