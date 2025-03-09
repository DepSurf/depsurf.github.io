# Function: <code>num_poisoned_pages_sub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "num_poisoned_pages_sub",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580949841,
      "name": "num_poisoned_pages_sub",
      "external": false,
      "loc": "include/linux/swapops.h:204",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "num_poisoned_pages_sub",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581104590,
      "name": "num_poisoned_pages_sub",
      "external": false,
      "loc": "include/linux/swapops.h:204",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "num_poisoned_pages_sub",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581179736,
      "name": "num_poisoned_pages_sub",
      "external": false,
      "loc": "include/linux/swapops.h:204",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void num_poisoned_pages_sub(long unsigned int pfn, long int i)
```

```json
{
  "name": "num_poisoned_pages_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583441923,
      "name": "num_poisoned_pages_sub",
      "external": true,
      "loc": "mm/memory-failure.c:83",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:__free_raw_hwp_pages"
      ],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444656,
      "name": "num_poisoned_pages_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void num_poisoned_pages_sub(long unsigned int pfn, long int i)
```

```json
{
  "name": "num_poisoned_pages_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583657677,
      "name": "num_poisoned_pages_sub",
      "external": true,
      "loc": "mm/memory-failure.c:84",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:__folio_free_raw_hwp"
      ],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659776,
      "name": "num_poisoned_pages_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void num_poisoned_pages_sub(long unsigned int pfn, long int i)
```

```json
{
  "name": "num_poisoned_pages_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583853775,
      "name": "num_poisoned_pages_sub",
      "external": true,
      "loc": "mm/memory-failure.c:83",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:__folio_free_raw_hwp"
      ],
      "caller_func": [
        "drivers/base/memory.c:remove_memory_block_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583854080,
      "name": "num_poisoned_pages_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void num_poisoned_pages_sub(long unsigned int pfn, long int i)
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
