# Function: <code>iommu_alloc_resv_region</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, int type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584789284,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1715",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584790784,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584878289,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1807",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584880080,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585298017,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1830",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585299856,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585538261,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1836",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585540432,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663920,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1893",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663920,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585891328,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2114",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891328,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586034016,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586034016,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586772152,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2535",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766800,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586947148,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2758",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586946368,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586830508,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2744",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828208,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587391660,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2829",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388544,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588699724,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2606",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698400,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type, gfp_t gfp)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590180316,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2667",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590178208,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type, gfp_t gfp)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590505388,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2673",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590500624,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type, gfp_t gfp)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590859209,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2949",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint",
        "drivers/iommu/virtio-iommu.c:viommu_probe_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590855504,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498835696,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions",
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/arm-smmu.c:arm_smmu_get_resv_regions",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_get_resv_regions",
        "drivers/iommu/virtio-iommu.c:viommu_add_device",
        "drivers/iommu/virtio-iommu.c:viommu_add_device",
        "drivers/iommu/virtio-iommu.c:viommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498835696,
      "name": "iommu_alloc_resv_region",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231441084,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231441084,
      "name": "iommu_alloc_resv_region",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292049624,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292052672,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794992,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794992,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585654176,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585654176,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984032,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984032,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
```

```json
{
  "name": "iommu_alloc_resv_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586091920,
      "name": "iommu_alloc_resv_region",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2172",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_insert_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions",
        "drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091920,
      "name": "iommu_alloc_resv_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, int type)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int type</code> ➡️ <code>enum iommu_resv_type type</code>
</li>
</ul>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iommu_resv_region * iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type)
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
