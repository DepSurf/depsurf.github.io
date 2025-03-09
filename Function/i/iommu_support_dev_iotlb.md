# Function: <code>iommu_support_dev_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584319883,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1440",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
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
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584666809,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1447",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
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
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584853473,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1461",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584942805,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1466",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585364175,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1449",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585606386,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1451",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585723168,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1327",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585723168,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950720,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1332",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950720,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586094016,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1343",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094016,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586837088,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1359",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586837088,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586892256,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1442",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586892256,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586773168,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1466",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773168,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328480,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1470",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328480,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588643088,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1400",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588643088,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585855136,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1343",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585855136,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585714160,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1343",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585714160,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586044032,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1343",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044032,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```

```json
{
  "name": "iommu_support_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586151456,
      "name": "iommu_support_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1343",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151456,
      "name": "iommu_support_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
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
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct device_domain_info * iommu_support_dev_iotlb(struct dmar_domain * domain, struct intel_iommu * iommu, u8 bus, u8 devfn)
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
