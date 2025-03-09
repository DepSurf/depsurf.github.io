# Function: <code>e820__mapped_any</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048928,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:76",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048928,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057808,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:76",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057808,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579062720,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:76",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062720,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579067296,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:75",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067296,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075984,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075984,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077984,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077984,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088992,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088992,
      "name": "e820__mapped_any",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090944,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090944,
      "name": "e820__mapped_any",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579097488,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097488,
      "name": "e820__mapped_any",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121152,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121152,
      "name": "e820__mapped_any",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579153856,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:aperture_valid",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579153856,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201920,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201920,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206016,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206016,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579235360,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:read_agp",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "drivers/char/agp/amd64-agp.c:agp_aperture_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579235360,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078336,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078336,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579011024,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579011024,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077920,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077920,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_any",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579082016,
      "name": "e820__mapped_any",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:100",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tboot.c:tboot_probe",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082016,
      "name": "e820__mapped_any",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```
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
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type)
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
