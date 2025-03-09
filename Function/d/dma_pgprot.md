# Function: <code>dma_pgprot</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580034880,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:158",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034880,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085360,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085360,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580145416,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:155",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_common_mmap"
      ],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145296,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124064,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:345",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124064,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128448,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:347",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128448,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271440,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:412",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271440,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442768,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:408",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442768,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686880,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:415",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686880,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763488,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:419",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763488,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849024,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:419",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_mmap",
        "kernel/dma/ops_helpers.c:dma_common_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849024,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491287300,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_common_mmap"
      ],
      "caller_func": [
        "kernel/dma/remap.c:arch_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_mmap",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491287104,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225294100,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225294100,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284213008,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284213008,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271803488,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271803488,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580054096,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054096,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999408,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999408,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580045632,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045632,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```

```json
{
  "name": "dma_pgprot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580096384,
      "name": "dma_pgprot",
      "external": true,
      "loc": "kernel/dma/mapping.c:170",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096384,
      "name": "dma_pgprot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
pgprot_t dma_pgprot(struct device * dev, pgprot_t prot, long unsigned int attrs)
```
</details>
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
