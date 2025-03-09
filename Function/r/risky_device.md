# Function: <code>risky_device</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool risky_device(struct pci_dev * pdev)
```

```json
{
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586846688,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:6042",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586868110,
      "name": "risky_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071586843440,
      "name": "risky_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586868172,
      "name": "risky_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool risky_device(struct pci_dev * pdev)
```

```json
{
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586901920,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5499",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591478168,
      "name": "risky_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071586897904,
      "name": "risky_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591478230,
      "name": "risky_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool risky_device(struct pci_dev * pdev)
```

```json
{
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586781264,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5487",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591418858,
      "name": "risky_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071586777680,
      "name": "risky_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591418920,
      "name": "risky_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
bool risky_device(struct pci_dev * pdev)
```

```json
{
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587336880,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:5548",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592473293,
      "name": "risky_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071587333120,
      "name": "risky_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592473355,
      "name": "risky_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
bool risky_device(struct pci_dev * pdev)
```

```json
{
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588651846,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4870",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594343054,
      "name": "risky_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071588647840,
      "name": "risky_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071594343126,
      "name": "risky_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590123704,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4745",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590438216,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4703",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "risky_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590784504,
      "name": "risky_device",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4602",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch",
        "drivers/iommu/intel/iommu.c:check_tylersburg_isoch"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
bool risky_device(struct pci_dev * pdev)
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool risky_device(struct pci_dev * pdev)
```
</details>
</li>
</ul>
