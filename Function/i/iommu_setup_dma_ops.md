# Function: <code>iommu_setup_dma_ops</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 size)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1142",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586786527,
      "name": "iommu_setup_dma_ops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071586785888,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 size)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1320",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591483171,
      "name": "iommu_setup_dma_ops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586968896,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 size)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1314",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591426700,
      "name": "iommu_setup_dma_ops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586850032,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 dma_limit)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592484694,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1331",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize",
        "drivers/iommu/virtio-iommu.c:viommu_probe_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592484694,
      "name": "iommu_setup_dma_ops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587411840,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 dma_limit)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594353763,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1488",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize",
        "drivers/iommu/virtio-iommu.c:viommu_probe_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594353763,
      "name": "iommu_setup_dma_ops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588726864,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 dma_limit)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590211296,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1572",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize",
        "drivers/iommu/virtio-iommu.c:viommu_probe_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590211296,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 dma_limit)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590532816,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1616",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize",
        "drivers/iommu/virtio-iommu.c:viommu_probe_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590532816,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 dma_limit)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590888464,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1737",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize",
        "drivers/iommu/virtio-iommu.c:viommu_probe_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590888464,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 size)
```

```json
{
  "name": "iommu_setup_dma_ops",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498849328,
      "name": "iommu_setup_dma_ops",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:1115",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/dma-mapping.c:arch_setup_dma_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498849328,
      "name": "iommu_setup_dma_ops",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 size)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 dma_limit</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 size</code>
</li>
</ul>
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void iommu_setup_dma_ops(struct device * dev, u64 dma_base, u64 size)
```
</details>
</li>
</ul>
