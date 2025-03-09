# Function: <code>match_hid_uid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584629547,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:175",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:get_alias"
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
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584814683,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:176",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:check_device",
        "drivers/iommu/amd_iommu.c:get_alias"
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
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584907399,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:205",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585327683,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:138",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:get_irq_domain",
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int match_hid_uid(struct device * dev, void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584612208,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:481",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585571661,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:139",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584612208,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int match_hid_uid(struct device * dev, void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584709840,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:514",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585693554,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:139",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709840,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584910960,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:511",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585920239,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:128",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd_iommu.c:get_alias"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910960,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585046672,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:534",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586064511,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:127",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046672,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585749552,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:512",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749552,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585868640,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:519",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868640,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585746416,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:520",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585746416,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228960,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:521",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228960,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587467264,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:543",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587467264,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588734128,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:535",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588734128,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589022192,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:550",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589022192,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589330688,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:539",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589330688,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "match_hid_uid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585825487,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:127",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584893696,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:534",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585684671,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:127",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893696,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584998256,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:534",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586014527,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:127",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998256,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```

```json
{
  "name": "match_hid_uid",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585104432,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/acpi/acpi_lpss.c:534",
      "file": "drivers/acpi/acpi_lpss.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586122479,
      "name": "match_hid_uid",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:127",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd_iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_group"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585104432,
      "name": "match_hid_uid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int match_hid_uid(struct device * dev, void * data)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * data</code> ➡️ <code>const void * data</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int match_hid_uid(struct device * dev, const void * data)
```
</details>
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
