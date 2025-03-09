# Function: <code>vfio_iommu_resv_exclude</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587048704,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1555",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048704,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884944,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1896",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884944,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587946496,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1923",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946496,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587827376,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2143",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827376,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588432320,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2145",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432320,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589832416,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2135",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589832416,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696624,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1555",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696624,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587003264,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1555",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587003264,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```

```json
{
  "name": "vfio_iommu_resv_exclude",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587110432,
      "name": "vfio_iommu_resv_exclude",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1555",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110432,
      "name": "vfio_iommu_resv_exclude",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int vfio_iommu_resv_exclude(struct list_head * iova, struct list_head * resv_regions)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
