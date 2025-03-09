# Function: <code>intel_cap_smts_sanity</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool intel_cap_smts_sanity()
```

```json
{
  "name": "intel_cap_smts_sanity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586809056,
      "name": "intel_cap_smts_sanity",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:187",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_nesting",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled",
        "drivers/iommu/intel/iommu.c:alloc_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586809056,
      "name": "intel_cap_smts_sanity",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool intel_cap_smts_sanity()
```

```json
{
  "name": "intel_cap_smts_sanity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368224,
      "name": "intel_cap_smts_sanity",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:187",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled",
        "drivers/iommu/intel/iommu.c:alloc_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368224,
      "name": "intel_cap_smts_sanity",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool intel_cap_smts_sanity()
```

```json
{
  "name": "intel_cap_smts_sanity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588679147,
      "name": "intel_cap_smts_sanity",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:196",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:alloc_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588679248,
      "name": "intel_cap_smts_sanity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool intel_cap_smts_sanity()
```

```json
{
  "name": "intel_cap_smts_sanity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590156486,
      "name": "intel_cap_smts_sanity",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:196",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590156640,
      "name": "intel_cap_smts_sanity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool intel_cap_smts_sanity()
```

```json
{
  "name": "intel_cap_smts_sanity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590470746,
      "name": "intel_cap_smts_sanity",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:194",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590470896,
      "name": "intel_cap_smts_sanity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool intel_cap_smts_sanity()
```

```json
{
  "name": "intel_cap_smts_sanity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590821274,
      "name": "intel_cap_smts_sanity",
      "external": true,
      "loc": "drivers/iommu/intel/cap_audit.c:194",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590821424,
      "name": "intel_cap_smts_sanity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool intel_cap_smts_sanity()
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
