# Function: <code>iommu_default_passthrough</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586023344,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586023344,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586762528,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2570",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_dma_ops",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762528,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586941248,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2793",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_dma_ops",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941248,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586823120,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2777",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823120,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615547795,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2862",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_subsys_init",
        "drivers/iommu/iommu.c:iommu_subsys_init"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383200,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617353314,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2639",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_subsys_init",
        "drivers/iommu/iommu.c:iommu_subsys_init"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588693584,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628089531,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2701",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_subsys_init",
        "drivers/iommu/iommu.c:iommu_subsys_init"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/init.c:amd_iommu_snp_enable",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590172464,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619855183,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2707",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_subsys_init",
        "drivers/iommu/iommu.c:iommu_subsys_init"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/init.c:amd_iommu_snp_enable",
        "drivers/iommu/amd/init.c:iommu_init_pci"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590494672,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622164031,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2983",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_subsys_init",
        "drivers/iommu/iommu.c:iommu_subsys_init"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/init.c:amd_iommu_snp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590847824,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498822624,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498822624,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231429440,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231429440,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292033472,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292033472,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585784320,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784320,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585643504,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585643504,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585973360,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585973360,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool iommu_default_passthrough()
```

```json
{
  "name": "iommu_default_passthrough",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586081088,
      "name": "iommu_default_passthrough",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2271",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops",
        "drivers/iommu/intel-iommu.c:init_dmars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586081088,
      "name": "iommu_default_passthrough",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool iommu_default_passthrough()
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool iommu_default_passthrough()
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
