# Function: <code>aux_domain_remove_dev</code>

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
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585955141,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5041",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586098421,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5325",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device"
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
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586852453,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5215",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void aux_domain_remove_dev(struct dmar_domain * domain, struct device * dev)
```

```json
{
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586907712,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4633",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907712,
      "name": "aux_domain_remove_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586788213,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4733",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device"
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
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587344789,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4718",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585859541,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5325",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device"
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
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585718565,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5325",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device"
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
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586048437,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5325",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device"
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
  "name": "aux_domain_remove_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586154981,
      "name": "aux_domain_remove_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:5325",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void aux_domain_remove_dev(struct dmar_domain * domain, struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void aux_domain_remove_dev(struct dmar_domain * domain, struct device * dev)
```
</details>
</li>
</ul>
