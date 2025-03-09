# Function: <code>clflush_cache_range_opt</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range_opt(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359344,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:277",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359344,
      "name": "clflush_cache_range_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void clflush_cache_range_opt(void * vaddr, unsigned int size)
```

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373936,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:278",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373936,
      "name": "clflush_cache_range_opt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579384007,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:278",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579423673,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:285",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579423369,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:285",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579426361,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:293",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579490107,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:293",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579570194,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:296",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579678530,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:314",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579692386,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:315",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579726914,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pat/set_memory.c:315",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:cpa_flush",
        "arch/x86/mm/pat/set_memory.c:arch_invalidate_pmem"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579379911,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:278",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309625,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:278",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579379831,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:278",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clflush_cache_range_opt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579388311,
      "name": "clflush_cache_range_opt",
      "external": false,
      "loc": "arch/x86/mm/pageattr.c:278",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:cpa_flush",
        "arch/x86/mm/pageattr.c:arch_invalidate_pmem"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void clflush_cache_range_opt(void * vaddr, unsigned int size)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void clflush_cache_range_opt(void * vaddr, unsigned int size)
```
</details>
</li>
</ul>
