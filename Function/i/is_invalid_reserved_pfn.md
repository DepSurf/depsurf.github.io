# Function: <code>is_invalid_reserved_pfn</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587049696,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:298",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587049696,
      "name": "is_invalid_reserved_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587880960,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:399",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880960,
      "name": "is_invalid_reserved_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587941952,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:412",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941952,
      "name": "is_invalid_reserved_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587837283,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:450",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
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
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588442372,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:451",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589827728,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:449",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_unpin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/vfio_iommu_type1.c:vfio_batch_unpin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589827728,
      "name": "is_invalid_reserved_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586697616,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:298",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697616,
      "name": "is_invalid_reserved_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587004256,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:298",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004256,
      "name": "is_invalid_reserved_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```

```json
{
  "name": "is_invalid_reserved_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587111424,
      "name": "is_invalid_reserved_pfn",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:298",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vfio_pin_pages_remote",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111424,
      "name": "is_invalid_reserved_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
bool is_invalid_reserved_pfn(long unsigned int pfn)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
