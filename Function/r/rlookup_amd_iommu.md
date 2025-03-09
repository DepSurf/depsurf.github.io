# Function: <code>rlookup_amd_iommu</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct amd_iommu * rlookup_amd_iommu(struct device * dev)
```

```json
{
  "name": "rlookup_amd_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066080,
      "name": "rlookup_amd_iommu",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:170",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:device_flush_iotlb",
        "drivers/iommu/amd/iommu.c:check_device",
        "drivers/iommu/amd/iommu.c:clone_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066080,
      "name": "rlookup_amd_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
struct amd_iommu * rlookup_amd_iommu(struct device * dev)
```

```json
{
  "name": "rlookup_amd_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590381024,
      "name": "rlookup_amd_iommu",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:170",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:device_flush_iotlb",
        "drivers/iommu/amd/iommu.c:clone_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590381024,
      "name": "rlookup_amd_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
struct amd_iommu * rlookup_amd_iommu(struct device * dev)
```

```json
{
  "name": "rlookup_amd_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590723120,
      "name": "rlookup_amd_iommu",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:173",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:set_remap_table_entry_alias",
        "drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_set_dirty_tracking",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd/iommu.c:do_iommu_domain_alloc",
        "drivers/iommu/amd/iommu.c:update_device_table",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:__domain_flush_pages",
        "drivers/iommu/amd/iommu.c:clone_alias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590723120,
      "name": "rlookup_amd_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct amd_iommu * rlookup_amd_iommu(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
