# Function: <code>iommu_set_dma_strict</code>

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
void iommu_set_dma_strict(bool strict)
```

```json
{
  "name": "iommu_set_dma_strict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586837648,
      "name": "iommu_set_dma_strict",
      "external": true,
      "loc": "drivers/iommu/iommu.c:347",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel/iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586837648,
      "name": "iommu_set_dma_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void iommu_set_dma_strict()
```

```json
{
  "name": "iommu_set_dma_strict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587398768,
      "name": "iommu_set_dma_strict",
      "external": true,
      "loc": "drivers/iommu/iommu.c:367",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587398768,
      "name": "iommu_set_dma_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void iommu_set_dma_strict()
```

```json
{
  "name": "iommu_set_dma_strict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709392,
      "name": "iommu_set_dma_strict",
      "external": true,
      "loc": "drivers/iommu/iommu.c:374",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709392,
      "name": "iommu_set_dma_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void iommu_set_dma_strict()
```

```json
{
  "name": "iommu_set_dma_strict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590191392,
      "name": "iommu_set_dma_strict",
      "external": true,
      "loc": "drivers/iommu/iommu.c:501",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590191392,
      "name": "iommu_set_dma_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void iommu_set_dma_strict()
```

```json
{
  "name": "iommu_set_dma_strict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590513136,
      "name": "iommu_set_dma_strict",
      "external": true,
      "loc": "drivers/iommu/iommu.c:571",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590513136,
      "name": "iommu_set_dma_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void iommu_set_dma_strict()
```

```json
{
  "name": "iommu_set_dma_strict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590868544,
      "name": "iommu_set_dma_strict",
      "external": true,
      "loc": "drivers/iommu/iommu.c:701",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/init.c:parse_amd_iommu_options",
        "drivers/iommu/amd/init.c:iommu_init_pci",
        "drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590868544,
      "name": "iommu_set_dma_strict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void iommu_set_dma_strict(bool strict)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool strict</code>
</li>
</ul>
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
