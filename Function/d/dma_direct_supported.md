# Function: <code>dma_direct_supported</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579947168,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:167",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947168,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995552,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:365",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995552,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037776,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037776,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580088016,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088016,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148800,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:516",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148800,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129264,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:472",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129264,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133568,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:472",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133568,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:514",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150144,
      "name": "dma_direct_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580276704,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:548",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922761,
      "name": "dma_direct_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580448592,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:579",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595993089,
      "name": "dma_direct_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580693312,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:578",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596511349,
      "name": "dma_direct_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580769936,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:567",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_set_coherent_mask",
        "kernel/dma/mapping.c:dma_set_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410486,
      "name": "dma_direct_supported.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071580855840,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491291144,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491291144,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225296548,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225296548,
      "name": "dma_direct_supported",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284217088,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_device",
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_cpu",
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_device",
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_cpu",
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_free_coherent",
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284217088,
      "name": "dma_direct_supported",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271806238,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271806238,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056848,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056848,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002064,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002064,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048288,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048288,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_direct_supported(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_direct_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099040,
      "name": "dma_direct_supported",
      "external": true,
      "loc": "kernel/dma/direct.c:393",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099040,
      "name": "dma_direct_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int dma_direct_supported(struct device * dev, u64 mask)
```
</details>
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
