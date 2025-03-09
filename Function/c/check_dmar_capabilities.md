# Function: <code>check_dmar_capabilities</code>

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
void check_dmar_capabilities(struct intel_iommu * a, struct intel_iommu * b)
```

```json
{
  "name": "check_dmar_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_dmar_capabilities",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:26",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586806400,
      "name": "check_dmar_capabilities",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
    },
    {
      "addr": 18446744071591421527,
      "name": "check_dmar_capabilities.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1377
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
void check_dmar_capabilities(struct intel_iommu * a, struct intel_iommu * b)
```

```json
{
  "name": "check_dmar_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_dmar_capabilities",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:26",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365568,
      "name": "check_dmar_capabilities",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
    },
    {
      "addr": 18446744071592477987,
      "name": "check_dmar_capabilities.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1377
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
void check_dmar_capabilities(struct intel_iommu * a, struct intel_iommu * b)
```

```json
{
  "name": "check_dmar_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_dmar_capabilities",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:26",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676512,
      "name": "check_dmar_capabilities",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
    },
    {
      "addr": 18446744071594347043,
      "name": "check_dmar_capabilities.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1377
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
void check_dmar_capabilities(struct intel_iommu * a, struct intel_iommu * b)
```

```json
{
  "name": "check_dmar_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590150400,
      "name": "check_dmar_capabilities",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:26",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590150400,
      "name": "check_dmar_capabilities",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2469
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
void check_dmar_capabilities(struct intel_iommu * a, struct intel_iommu * b)
```

```json
{
  "name": "check_dmar_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590464816,
      "name": "check_dmar_capabilities",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:26",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590464816,
      "name": "check_dmar_capabilities",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2281
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
void check_dmar_capabilities(struct intel_iommu * a, struct intel_iommu * b)
```

```json
{
  "name": "check_dmar_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590815344,
      "name": "check_dmar_capabilities",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:26",
      "file": "drivers/iommu/intel/cap_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/cap_audit.c:intel_cap_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590815344,
      "name": "check_dmar_capabilities",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2281
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
void check_dmar_capabilities(struct intel_iommu * a, struct intel_iommu * b)
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
