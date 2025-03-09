# Function: <code>kfence_guarded_alloc</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * kfence_guarded_alloc(struct kmem_cache * cache, size_t size, gfp_t gfp)
```

```json
{
  "name": "kfence_guarded_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236272,
      "name": "kfence_guarded_alloc",
      "external": false,
      "loc": "mm/kfence/core.c:261",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236272,
      "name": "kfence_guarded_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
void * kfence_guarded_alloc(struct kmem_cache * cache, size_t size, gfp_t gfp, long unsigned int * stack_entries, size_t num_stack_entries, u32 alloc_stack_hash)
```

```json
{
  "name": "kfence_guarded_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582706368,
      "name": "kfence_guarded_alloc",
      "external": false,
      "loc": "mm/kfence/core.c:355",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582706368,
      "name": "kfence_guarded_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1005
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
void * kfence_guarded_alloc(struct kmem_cache * cache, size_t size, gfp_t gfp, long unsigned int * stack_entries, size_t num_stack_entries, u32 alloc_stack_hash)
```

```json
{
  "name": "kfence_guarded_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232016,
      "name": "kfence_guarded_alloc",
      "external": false,
      "loc": "mm/kfence/core.c:354",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232016,
      "name": "kfence_guarded_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1003
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
void * kfence_guarded_alloc(struct kmem_cache * cache, size_t size, gfp_t gfp, long unsigned int * stack_entries, size_t num_stack_entries, u32 alloc_stack_hash)
```

```json
{
  "name": "kfence_guarded_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452448,
      "name": "kfence_guarded_alloc",
      "external": false,
      "loc": "mm/kfence/core.c:382",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452448,
      "name": "kfence_guarded_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
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
void * kfence_guarded_alloc(struct kmem_cache * cache, size_t size, gfp_t gfp, long unsigned int * stack_entries, size_t num_stack_entries, u32 alloc_stack_hash)
```

```json
{
  "name": "kfence_guarded_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583644016,
      "name": "kfence_guarded_alloc",
      "external": false,
      "loc": "mm/kfence/core.c:390",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:__kfence_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644016,
      "name": "kfence_guarded_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1070
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void * kfence_guarded_alloc(struct kmem_cache * cache, size_t size, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int * stack_entries</code>
</li>
<li>
<b>Param added. </b>
<code>size_t num_stack_entries</code>
</li>
<li>
<b>Param added. </b>
<code>u32 alloc_stack_hash</code>
</li>
</ul>
</details>
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
