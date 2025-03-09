# Function: <code>mhp_memmap_on_memory</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool mhp_memmap_on_memory()
```

```json
{
  "name": "mhp_memmap_on_memory",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594682802,
      "name": "mhp_memmap_on_memory",
      "external": true,
      "loc": "mm/memory_hotplug.c:66",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:mhp_supports_memmap_on_memory"
      ],
      "caller_func": [
        "mm/hugetlb_vmemmap.c:hugetlb_vmemmap_sysctls_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985735,
      "name": "mhp_memmap_on_memory.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582467904,
      "name": "mhp_memmap_on_memory",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mhp_memmap_on_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596419154,
      "name": "mhp_memmap_on_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:53",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:mhp_supports_memmap_on_memory"
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
  "name": "mhp_memmap_on_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596959218,
      "name": "mhp_memmap_on_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:52",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/memory_hotplug.c:mhp_supports_memmap_on_memory"
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
  "name": "mhp_memmap_on_memory",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597886941,
      "name": "mhp_memmap_on_memory",
      "external": false,
      "loc": "mm/memory_hotplug.c:120",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_remove_memory"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool mhp_memmap_on_memory()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool mhp_memmap_on_memory()
```
</details>
</li>
</ul>
