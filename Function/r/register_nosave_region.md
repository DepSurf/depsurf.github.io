# Function: <code>register_nosave_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595000100,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:368",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820_mark_nosave_regions",
        "arch/x86/kernel/e820.c:e820_mark_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595057249,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:368",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595163634,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:367",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820_mark_nosave_regions",
        "arch/x86/kernel/e820.c:e820_mark_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595222946,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:367",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595406387,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:369",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820_mark_nosave_regions",
        "arch/x86/kernel/e820.c:e820_mark_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595466021,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:369",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596325911,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:371",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596387212,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:371",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602643949,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:375",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602705731,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:375",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602813630,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:375",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602878289,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:375",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604608677,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:377",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604675411,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:377",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604704205,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:430",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604774456,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:430",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604716593,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604800258,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609063775,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:434",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609140703,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:434",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:allocate_aperture"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612127151,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:434",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612210752,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:434",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:allocate_aperture"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614267075,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:434",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614354295,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:434",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "register_nosave_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615327509,
      "name": "register_nosave_region",
      "external": true,
      "loc": "kernel/power/snapshot.c:981",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615327509,
      "name": "register_nosave_region",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "register_nosave_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617110775,
      "name": "register_nosave_region",
      "external": true,
      "loc": "kernel/power/snapshot.c:985",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617110775,
      "name": "register_nosave_region",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "register_nosave_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627776336,
      "name": "register_nosave_region",
      "external": true,
      "loc": "kernel/power/snapshot.c:985",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627776336,
      "name": "register_nosave_region",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "register_nosave_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619539216,
      "name": "register_nosave_region",
      "external": true,
      "loc": "kernel/power/snapshot.c:985",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619539216,
      "name": "register_nosave_region",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "register_nosave_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621838112,
      "name": "register_nosave_region",
      "external": true,
      "loc": "kernel/power/snapshot.c:995",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621838112,
      "name": "register_nosave_region",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 222
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
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604642883,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714200,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604610817,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604682143,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720675,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604791767,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_nosave_region",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720705,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__register_nosave_regions",
        "arch/x86/kernel/e820.c:e820__register_nosave_regions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604804388,
      "name": "register_nosave_region",
      "external": false,
      "loc": "include/linux/suspend.h:432",
      "file": "arch/x86/kernel/aperture_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn)
```
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
