# Function: <code>acpi_dev_hid_uid_match</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```

```json
{
  "name": "acpi_dev_hid_uid_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667808,
      "name": "acpi_dev_hid_uid_match",
      "external": true,
      "loc": "drivers/acpi/utils.c:738",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/iommu/amd/iommu.c:get_devid",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667808,
      "name": "acpi_dev_hid_uid_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```

```json
{
  "name": "acpi_dev_hid_uid_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585793584,
      "name": "acpi_dev_hid_uid_match",
      "external": true,
      "loc": "drivers/acpi/utils.c:734",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793584,
      "name": "acpi_dev_hid_uid_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```

```json
{
  "name": "acpi_dev_hid_uid_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673360,
      "name": "acpi_dev_hid_uid_match",
      "external": true,
      "loc": "drivers/acpi/utils.c:728",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673360,
      "name": "acpi_dev_hid_uid_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```

```json
{
  "name": "acpi_dev_hid_uid_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152928,
      "name": "acpi_dev_hid_uid_match",
      "external": true,
      "loc": "drivers/acpi/utils.c:742",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152928,
      "name": "acpi_dev_hid_uid_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```

```json
{
  "name": "acpi_dev_hid_uid_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587386176,
      "name": "acpi_dev_hid_uid_match",
      "external": true,
      "loc": "drivers/acpi/utils.c:742",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_detach_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:check_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587386176,
      "name": "acpi_dev_hid_uid_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```

```json
{
  "name": "acpi_dev_hid_uid_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588636272,
      "name": "acpi_dev_hid_uid_match",
      "external": true,
      "loc": "drivers/acpi/utils.c:780",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:check_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588636272,
      "name": "acpi_dev_hid_uid_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```

```json
{
  "name": "acpi_dev_hid_uid_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924016,
      "name": "acpi_dev_hid_uid_match",
      "external": true,
      "loc": "drivers/acpi/utils.c:780",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links",
        "drivers/acpi/acpi_lpss.c:match_hid_uid",
        "drivers/iommu/amd/iommu.c:irq_remapping_alloc",
        "drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions",
        "drivers/iommu/amd/iommu.c:amd_iommu_device_group",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:amd_iommu_probe_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu",
        "drivers/iommu/amd/iommu.c:rlookup_amd_iommu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924016,
      "name": "acpi_dev_hid_uid_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device * adev, const char * hid2, const char * uid2)
```
</details>
</li>
</ul>
