# Function: <code>dma_direct_get_required_mask</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994512,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:54",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994512,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036624,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036624,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086864,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:iommu_need_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086864,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147664,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:40",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147664,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580125488,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:39",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125488,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129808,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:39",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129808,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:39",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592149918,
      "name": "dma_direct_get_required_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580273232,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:39",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922624,
      "name": "dma_direct_get_required_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580444736,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:39",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595993029,
      "name": "dma_direct_get_required_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580689088,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:39",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596511289,
      "name": "dma_direct_get_required_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580765696,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:39",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_addressing_limited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410278,
      "name": "dma_direct_get_required_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580851440,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491289760,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491289760,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225295324,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225295324,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284215744,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_get_required_mask",
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284215744,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271805278,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271805278,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055744,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:iommu_need_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055744,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000912,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:iommu_need_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000912,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047136,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:iommu_need_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047136,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 dma_direct_get_required_mask(struct device * dev)
```

```json
{
  "name": "dma_direct_get_required_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097888,
      "name": "dma_direct_get_required_mask",
      "external": true,
      "loc": "kernel/dma/direct.c:46",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_required_mask",
        "drivers/iommu/intel-iommu.c:intel_get_required_mask",
        "drivers/iommu/intel-iommu.c:iommu_need_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097888,
      "name": "dma_direct_get_required_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
u64 dma_direct_get_required_mask(struct device * dev)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
