# Function: <code>iommu_group_alloc_default_domain</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1460",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768464,
      "name": "iommu_group_alloc_default_domain.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071586776793,
      "name": "iommu_group_alloc_default_domain.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type * bus, struct iommu_group * group, unsigned int type)
```

```json
{
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1494",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949408,
      "name": "iommu_group_alloc_default_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    },
    {
      "addr": 18446744071591482789,
      "name": "iommu_group_alloc_default_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type * bus, struct iommu_group * group, unsigned int type)
```

```json
{
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1523",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833952,
      "name": "iommu_group_alloc_default_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071591426380,
      "name": "iommu_group_alloc_default_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int iommu_group_alloc_default_domain(struct bus_type * bus, struct iommu_group * group, unsigned int type)
```

```json
{
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1538",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587396752,
      "name": "iommu_group_alloc_default_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071592483462,
      "name": "iommu_group_alloc_default_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int iommu_group_alloc_default_domain(struct bus_type * bus, struct iommu_group * group, unsigned int type)
```

```json
{
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1512",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:bus_iommu_probe",
        "drivers/iommu/iommu.c:iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588707104,
      "name": "iommu_group_alloc_default_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071594352515,
      "name": "iommu_group_alloc_default_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int iommu_group_alloc_default_domain(struct bus_type * bus, struct iommu_group * group, unsigned int type)
```

```json
{
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590177552,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1633",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/iommu.c:bus_iommu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590177552,
      "name": "iommu_group_alloc_default_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590511208,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1638",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_setup_default_domain"
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
  "name": "iommu_group_alloc_default_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590866029,
      "name": "iommu_group_alloc_default_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:1789",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_setup_default_domain"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type * bus, struct iommu_group * group, unsigned int type)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int iommu_group_alloc_default_domain(struct bus_type * bus, struct iommu_group * group, unsigned int type)
```
</details>
</li>
</ul>
