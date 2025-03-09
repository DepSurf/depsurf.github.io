# Function: <code>init_iommu_from_acpi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595266642,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:779",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595448364,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:878",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595448364,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1794
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595702704,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:980",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595702704,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1794
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596625678,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:989",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596625678,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1823
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602955726,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1124",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602955726,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1823
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603128462,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1124",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603128462,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1854
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604931293,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1151",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:early_amd_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604931293,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1854
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605041462,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1139",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605041462,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1876
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605078238,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1140",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605078238,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1887
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609366525,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1117",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609366525,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1707
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612437965,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1180",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612437965,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1707
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614578754,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1176",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614578754,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1891
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615533956,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1187",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615533956,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 2539
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617339265,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1193",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617339265,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 2555
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628071424,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1291",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628071424,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 3687
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619837488,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1326",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619837488,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 3557
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622146288,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd/init.c:1341",
      "file": "drivers/iommu/amd/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:init_iommu_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622146288,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 3557
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604977861,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1140",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604977861,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1887
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604942162,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1140",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604942162,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1887
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605058561,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1140",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605058561,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1887
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```

```json
{
  "name": "init_iommu_from_acpi",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605082432,
      "name": "init_iommu_from_acpi",
      "external": false,
      "loc": "drivers/iommu/amd_iommu_init.c:1140",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:init_iommu_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605082432,
      "name": "init_iommu_from_acpi",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1887
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int init_iommu_from_acpi(struct amd_iommu * iommu, struct ivhd_header * h)
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
