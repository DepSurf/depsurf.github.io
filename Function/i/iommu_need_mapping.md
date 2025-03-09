# Function: <code>iommu_need_mapping</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool iommu_need_mapping(struct device * dev)
```

```json
{
  "name": "iommu_need_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585968701,
      "name": "iommu_need_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3449",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_free_coherent",
        "drivers/iommu/intel-iommu.c:intel_unmap_resource",
        "drivers/iommu/intel-iommu.c:intel_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968576,
      "name": "iommu_need_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071585973884,
      "name": "iommu_need_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool iommu_need_mapping(struct device * dev)
```

```json
{
  "name": "iommu_need_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586114048,
      "name": "iommu_need_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3461",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_free_coherent",
        "drivers/iommu/intel-iommu.c:intel_unmap_resource",
        "drivers/iommu/intel-iommu.c:intel_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586113904,
      "name": "iommu_need_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071586119403,
      "name": "iommu_need_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool iommu_need_mapping(struct device * dev)
```

```json
{
  "name": "iommu_need_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585874288,
      "name": "iommu_need_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3461",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_free_coherent",
        "drivers/iommu/intel-iommu.c:intel_alloc_coherent",
        "drivers/iommu/intel-iommu.c:intel_unmap_resource",
        "drivers/iommu/intel-iommu.c:intel_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874144,
      "name": "iommu_need_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071585879761,
      "name": "iommu_need_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool iommu_need_mapping(struct device * dev)
```

```json
{
  "name": "iommu_need_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585734192,
      "name": "iommu_need_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3461",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_free_coherent",
        "drivers/iommu/intel-iommu.c:intel_unmap_resource",
        "drivers/iommu/intel-iommu.c:intel_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585734048,
      "name": "iommu_need_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071585739547,
      "name": "iommu_need_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool iommu_need_mapping(struct device * dev)
```

```json
{
  "name": "iommu_need_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586064064,
      "name": "iommu_need_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3461",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_free_coherent",
        "drivers/iommu/intel-iommu.c:intel_unmap_resource",
        "drivers/iommu/intel-iommu.c:intel_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586063920,
      "name": "iommu_need_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071586069419,
      "name": "iommu_need_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool iommu_need_mapping(struct device * dev)
```

```json
{
  "name": "iommu_need_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586172192,
      "name": "iommu_need_mapping",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3461",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_unmap_sg",
        "drivers/iommu/intel-iommu.c:intel_free_coherent",
        "drivers/iommu/intel-iommu.c:intel_unmap_resource",
        "drivers/iommu/intel-iommu.c:intel_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586172048,
      "name": "iommu_need_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071586177623,
      "name": "iommu_need_mapping.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool iommu_need_mapping(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool iommu_need_mapping(struct device * dev)
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
bool iommu_need_mapping(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool iommu_need_mapping(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool iommu_need_mapping(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool iommu_need_mapping(struct device * dev)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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
