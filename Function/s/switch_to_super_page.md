# Function: <code>switch_to_super_page</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void switch_to_super_page(struct dmar_domain * domain, long unsigned int start_pfn, long unsigned int end_pfn, int level)
```

```json
{
  "name": "switch_to_super_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586786208,
      "name": "switch_to_super_page",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2308",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:__domain_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586786208,
      "name": "switch_to_super_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void switch_to_super_page(struct dmar_domain * domain, long unsigned int start_pfn, long unsigned int end_pfn, int level)
```

```json
{
  "name": "switch_to_super_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switch_to_super_page",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2300",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:__domain_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342880,
      "name": "switch_to_super_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
    },
    {
      "addr": 18446744071592475009,
      "name": "switch_to_super_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void switch_to_super_page(struct dmar_domain * domain, long unsigned int start_pfn, long unsigned int end_pfn, int level)
```

```json
{
  "name": "switch_to_super_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switch_to_super_page",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2192",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:__domain_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588655472,
      "name": "switch_to_super_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071594344639,
      "name": "switch_to_super_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void switch_to_super_page(struct dmar_domain * domain, long unsigned int start_pfn, long unsigned int end_pfn, int level)
```

```json
{
  "name": "switch_to_super_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switch_to_super_page",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2151",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:__domain_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590128992,
      "name": "switch_to_super_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071596243285,
      "name": "switch_to_super_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void switch_to_super_page(struct dmar_domain * domain, long unsigned int start_pfn, long unsigned int end_pfn, int level)
```

```json
{
  "name": "switch_to_super_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switch_to_super_page",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2113",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:__domain_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590444032,
      "name": "switch_to_super_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
    },
    {
      "addr": 18446744071596771504,
      "name": "switch_to_super_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void switch_to_super_page(struct dmar_domain * domain, long unsigned int start_pfn, long unsigned int end_pfn, int level)
```

```json
{
  "name": "switch_to_super_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "switch_to_super_page",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:2024",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:__domain_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590790736,
      "name": "switch_to_super_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071597680100,
      "name": "switch_to_super_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void switch_to_super_page(struct dmar_domain * domain, long unsigned int start_pfn, long unsigned int end_pfn, int level)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
