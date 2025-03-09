# Function: <code>cap_audit_hotplug</code>

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
int cap_audit_hotplug(struct intel_iommu * iommu, enum cap_audit_type type)
```

```json
{
  "name": "cap_audit_hotplug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cap_audit_hotplug",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:75",
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
      "addr": 18446744071586807360,
      "name": "cap_audit_hotplug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1439
    },
    {
      "addr": 18446744071591422904,
      "name": "cap_audit_hotplug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int cap_audit_hotplug(struct intel_iommu * iommu, enum cap_audit_type type)
```

```json
{
  "name": "cap_audit_hotplug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cap_audit_hotplug",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:75",
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
      "addr": 18446744071587366528,
      "name": "cap_audit_hotplug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1439
    },
    {
      "addr": 18446744071592479364,
      "name": "cap_audit_hotplug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int cap_audit_hotplug(struct intel_iommu * iommu, enum cap_audit_type type)
```

```json
{
  "name": "cap_audit_hotplug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cap_audit_hotplug",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:75",
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
      "addr": 18446744071588677488,
      "name": "cap_audit_hotplug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1452
    },
    {
      "addr": 18446744071594348420,
      "name": "cap_audit_hotplug.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1569
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
int cap_audit_hotplug(struct intel_iommu * iommu, enum cap_audit_type type)
```

```json
{
  "name": "cap_audit_hotplug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590152896,
      "name": "cap_audit_hotplug",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:75",
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
      "addr": 18446744071590152896,
      "name": "cap_audit_hotplug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3333
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
int cap_audit_hotplug(struct intel_iommu * iommu, enum cap_audit_type type)
```

```json
{
  "name": "cap_audit_hotplug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590467120,
      "name": "cap_audit_hotplug",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:74",
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
      "addr": 18446744071590467120,
      "name": "cap_audit_hotplug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3357
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
int cap_audit_hotplug(struct intel_iommu * iommu, enum cap_audit_type type)
```

```json
{
  "name": "cap_audit_hotplug",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590817648,
      "name": "cap_audit_hotplug",
      "external": false,
      "loc": "drivers/iommu/intel/cap_audit.c:74",
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
      "addr": 18446744071590817648,
      "name": "cap_audit_hotplug",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3357
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
int cap_audit_hotplug(struct intel_iommu * iommu, enum cap_audit_type type)
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
