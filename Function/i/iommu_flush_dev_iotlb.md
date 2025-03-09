# Function: <code>iommu_flush_dev_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void iommu_flush_dev_iotlb(struct dmar_domain * domain, u64 addr, unsigned int mask)
```

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584310160,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1513",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel-iommu.c:flush_unmaps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584310160,
      "name": "iommu_flush_dev_iotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584659702,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1549",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659088,
      "name": "iommu_flush_dev_iotlb.part.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584845895,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1563",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845280,
      "name": "iommu_flush_dev_iotlb.part.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584934093,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1568",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:flush_unmaps_timeout",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584933488,
      "name": "iommu_flush_dev_iotlb.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585355667,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1551",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585355088,
      "name": "iommu_flush_dev_iotlb.part.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585598754,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1567",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598208,
      "name": "iommu_flush_dev_iotlb.part.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585723938,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1444",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585723392,
      "name": "iommu_flush_dev_iotlb.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585951698,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1452",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585951408,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586095154,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1463",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094608,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586845551,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1478",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iova",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iova",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586842848,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586901455,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1580",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586900784,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780563,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1604",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586779888,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587334949,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1608",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334064,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588649915,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1526",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648304,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590122263,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1494",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590121088,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590435751,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1464",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590434544,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590782248,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1333",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590781056,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585856274,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1463",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585855728,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585715298,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1463",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585714752,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586045170,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1463",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044624,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_flush_dev_iotlb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586153202,
      "name": "iommu_flush_dev_iotlb",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1463",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:iommu_flush_iova",
        "drivers/iommu/intel-iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152656,
      "name": "iommu_flush_dev_iotlb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void iommu_flush_dev_iotlb(struct dmar_domain * domain, u64 addr, unsigned int mask)
```
</details>
</li>
</ul>
