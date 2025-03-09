# Function: <code>amd_iommu_domain_flush_tlb_pde</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_flush_tlb_pde",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586752361,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1270",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach"
      ],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586748480,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_flush_tlb_pde",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587304020,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1319",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach"
      ],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587301968,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_flush_tlb_pde",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588613296,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1341",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach"
      ],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588620128,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_flush_tlb_pde",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590076544,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1423",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach"
      ],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590082928,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void amd_iommu_domain_flush_tlb_pde(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_flush_tlb_pde",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590386144,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1443",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach"
      ],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590394768,
      "name": "amd_iommu_domain_flush_tlb_pde",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain * domain)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void amd_iommu_domain_flush_tlb_pde(struct protection_domain * domain)
```
</details>
</li>
</ul>
