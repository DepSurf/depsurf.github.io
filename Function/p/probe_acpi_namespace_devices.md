# Function: <code>probe_acpi_namespace_devices</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605053111,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4609",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605090079,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4880",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int probe_acpi_namespace_devices()
```

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609374131,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4779",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609374131,
      "name": "probe_acpi_namespace_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 253
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
int probe_acpi_namespace_devices()
```

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612445391,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4176",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612445391,
      "name": "probe_acpi_namespace_devices",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614589488,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4262",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615546032,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:4251",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617351536,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3996",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628087324,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3874",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
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
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619853012,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3762",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
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
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622161889,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3611",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604989680,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4880",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604954003,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4880",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605070402,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4880",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
  "name": "probe_acpi_namespace_devices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605094273,
      "name": "probe_acpi_namespace_devices",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:4880",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int probe_acpi_namespace_devices()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int probe_acpi_namespace_devices()
```
</details>
</li>
</ul>
