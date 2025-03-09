# Function: <code>flush_cache_range</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:26",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581879409,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582279072,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582771583,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582988832,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583163157,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:35",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/arm64/include/asm/cacheflush.h:107",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void flush_cache_range(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "flush_cache_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224496456,
      "name": "flush_cache_range",
      "external": true,
      "loc": "arch/arm/mm/flush.c:79",
      "file": "arch/arm/mm/flush.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/debug_core.c:kgdb_flush_swbreak_addr",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:unmap_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224496456,
      "name": "flush_cache_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:29",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:29",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:29",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:29",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:29",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "arch/riscv/include/asm/cacheflush.h:29",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "flush_cache_range",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "flush_cache_range",
      "external": false,
      "loc": "include/asm-generic/cacheflush.h:33",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void flush_cache_range(struct vm_area_struct * vma, long unsigned int start, long unsigned int end)
```
</details>
</li>
</ul>
