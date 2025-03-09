# Function: <code>get_dev_table</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dev_table_entry * get_dev_table(struct amd_iommu * iommu)
```

```json
{
  "name": "get_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590073839,
      "name": "get_dev_table",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:122",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:clone_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:amd_iommu_apply_erratum_63",
        "drivers/iommu/amd/init.c:amd_iommu_apply_erratum_63",
        "drivers/iommu/amd/init.c:amd_iommu_apply_erratum_63",
        "drivers/iommu/amd/init.c:iommu_set_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590081328,
      "name": "get_dev_table",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dev_table_entry * get_dev_table(struct amd_iommu * iommu)
```

```json
{
  "name": "get_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590385681,
      "name": "get_dev_table",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:122",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:clone_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_set_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590393472,
      "name": "get_dev_table",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dev_table_entry * get_dev_table(struct amd_iommu * iommu)
```

```json
{
  "name": "get_dev_table",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590736411,
      "name": "get_dev_table",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:125",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_set_dirty_tracking",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:set_dte_entry",
        "drivers/iommu/amd/iommu.c:iommu_print_event",
        "drivers/iommu/amd/iommu.c:clone_alias"
      ],
      "caller_func": [
        "drivers/iommu/amd/init.c:iommu_set_device_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590731600,
      "name": "get_dev_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct dev_table_entry * get_dev_table(struct amd_iommu * iommu)
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
