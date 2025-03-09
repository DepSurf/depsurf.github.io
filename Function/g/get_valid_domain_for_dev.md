# Function: <code>get_valid_domain_for_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584328683,
      "name": "get_valid_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3368",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single",
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid"
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
  "name": "get_valid_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584677120,
      "name": "get_valid_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3429",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
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
  "name": "get_valid_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584863584,
      "name": "get_valid_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3520",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:intel_map_sg",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain * get_valid_domain_for_dev(struct device * dev)
```

```json
{
  "name": "get_valid_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584950736,
      "name": "get_valid_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3481",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950736,
      "name": "get_valid_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain * get_valid_domain_for_dev(struct device * dev)
```

```json
{
  "name": "get_valid_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585371856,
      "name": "get_valid_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3489",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585371856,
      "name": "get_valid_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct dmar_domain * get_valid_domain_for_dev(struct device * dev)
```

```json
{
  "name": "get_valid_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_valid_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3545",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:__intel_map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585614112,
      "name": "get_valid_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    },
    {
      "addr": 18446744071585617910,
      "name": "get_valid_domain_for_dev.cold.98",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct dmar_domain * get_valid_domain_for_dev(struct device * dev)
```

```json
{
  "name": "get_valid_domain_for_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_valid_domain_for_dev",
      "external": true,
      "loc": "drivers/iommu/intel-iommu.c:3561",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:__intel_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585742070,
      "name": "get_valid_domain_for_dev.cold.103",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585738576,
      "name": "get_valid_domain_for_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct dmar_domain * get_valid_domain_for_dev(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct dmar_domain * get_valid_domain_for_dev(struct device * dev)
```
</details>
</li>
</ul>
