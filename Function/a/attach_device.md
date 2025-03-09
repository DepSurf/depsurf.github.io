# Function: <code>attach_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584285591,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2071",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
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
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584632648,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1951",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
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
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584817228,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2044",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
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
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584906563,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2291",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585321536,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2062",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321536,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585561856,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2064",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585561856,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585688096,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2146",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688096,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585915520,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2128",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585915520,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586059952,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2156",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059952,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586812768,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2017",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586812768,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872288,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:2108",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872288,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586750368,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1569",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750368,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1618",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304064,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
    },
    {
      "addr": 18446744071592469411,
      "name": "attach_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1640",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588616240,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 735
    },
    {
      "addr": 18446744071594339169,
      "name": "attach_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1746",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590078656,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
    },
    {
      "addr": 18446744071596240758,
      "name": "attach_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1771",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590390496,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
    },
    {
      "addr": 18446744071596768860,
      "name": "attach_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590735007,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1868",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585820928,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2156",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585820928,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585680112,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2156",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680112,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586009968,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2156",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009968,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
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
int attach_device(struct device * dev, struct protection_domain * domain)
```

```json
{
  "name": "attach_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118832,
      "name": "attach_device",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2156",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118832,
      "name": "attach_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int attach_device(struct device * dev, struct protection_domain * domain)
```
</details>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int attach_device(struct device * dev, struct protection_domain * domain)
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
int attach_device(struct device * dev, struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int attach_device(struct device * dev, struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int attach_device(struct device * dev, struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int attach_device(struct device * dev, struct protection_domain * domain)
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
