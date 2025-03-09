# Function: <code>iommu_enable_dev_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584309968,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1461",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584309968,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584658784,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1491",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584658784,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584844976,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1505",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584844976,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584935488,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1510",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584935488,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585356720,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1493",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356720,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585598928,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1495",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598928,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585722864,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1371",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585722864,
      "name": "iommu_enable_dev_iotlb",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585950352,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1376",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950352,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093648,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1387",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093648,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586842448,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1403",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842448,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586894320,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1491",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894320,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586774224,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1515",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586774224,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587329760,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1519",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587329760,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588644096,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1437",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588644096,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585854768,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1387",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585854768,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585713792,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1387",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713792,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043664,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1387",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043664,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```

```json
{
  "name": "iommu_enable_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151088,
      "name": "iommu_enable_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1387",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel-iommu.c:domain_context_mapping_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151088,
      "name": "iommu_enable_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
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
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iommu_enable_dev_iotlb(struct device_domain_info * info)
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
