# Function: <code>intel_cap_audit</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu * iommu)
```

```json
{
  "name": "intel_cap_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cap_audit",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:171",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591424475,
      "name": "intel_cap_audit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071586808800,
      "name": "intel_cap_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu * iommu)
```

```json
{
  "name": "intel_cap_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cap_audit",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:171",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592480935,
      "name": "intel_cap_audit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071587367968,
      "name": "intel_cap_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu * iommu)
```

```json
{
  "name": "intel_cap_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_cap_audit",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:180",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594349989,
      "name": "intel_cap_audit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071588678944,
      "name": "intel_cap_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu * iommu)
```

```json
{
  "name": "intel_cap_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590156256,
      "name": "intel_cap_audit",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:180",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590156256,
      "name": "intel_cap_audit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu * iommu)
```

```json
{
  "name": "intel_cap_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590470496,
      "name": "intel_cap_audit",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:178",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590470496,
      "name": "intel_cap_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu * iommu)
```

```json
{
  "name": "intel_cap_audit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590821024,
      "name": "intel_cap_audit",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:178",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_add",
        "drivers/iommu/intel/iommu.c:init_dmars",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add",
        "drivers/iommu/intel/irq_remapping.c:dmar_ir_add",
        "drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590821024,
      "name": "intel_cap_audit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int intel_cap_audit(enum cap_audit_type type, struct intel_iommu * iommu)
```
</details>
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
