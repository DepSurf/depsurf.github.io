# Function: <code>set_domain_for_dev</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain * set_domain_for_dev(struct device * dev, struct dmar_domain * domain)
```

```json
{
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584861344,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2547",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:__get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584861344,
      "name": "set_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain * set_domain_for_dev(struct device * dev, struct dmar_domain * domain)
```

```json
{
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584950496,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2555",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950496,
      "name": "set_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
struct dmar_domain * set_domain_for_dev(struct device * dev, struct dmar_domain * domain)
```

```json
{
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585371616,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2579",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585371616,
      "name": "set_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain * set_domain_for_dev(struct device * dev, struct dmar_domain * domain)
```

```json
{
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585613856,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2635",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585613856,
      "name": "set_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dmar_domain * set_domain_for_dev(struct device * dev, struct dmar_domain * domain)
```

```json
{
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585738320,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2632",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:get_valid_domain_for_dev",
        "drivers/iommu/intel-iommu.c:iommu_prepare_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738320,
      "name": "set_domain_for_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585967621,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2621",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
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
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586112885,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2632",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585873125,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2632",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
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
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585733029,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2632",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
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
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586062901,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2632",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
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
  "name": "set_domain_for_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586171039,
      "name": "set_domain_for_dev",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:2632",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct dmar_domain * set_domain_for_dev(struct device * dev, struct dmar_domain * domain)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
struct dmar_domain * set_domain_for_dev(struct device * dev, struct dmar_domain * domain)
```
</details>
</li>
</ul>
