# Function: <code>vfio_iommu_iova_free</code>

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
void vfio_iommu_iova_free(struct list_head * iova)
```

```json
{
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587048240,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1613",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048240,
      "name": "vfio_iommu_iova_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587885609,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1954",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587947153,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1981",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587829361,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2201",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
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
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588434801,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2203",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
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
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589835163,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2193",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
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
void vfio_iommu_iova_free(struct list_head * iova)
```

```json
{
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696160,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1613",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696160,
      "name": "vfio_iommu_iova_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void vfio_iommu_iova_free(struct list_head * iova)
```

```json
{
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587002800,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1613",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002800,
      "name": "vfio_iommu_iova_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void vfio_iommu_iova_free(struct list_head * iova)
```

```json
{
  "name": "vfio_iommu_iova_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587109968,
      "name": "vfio_iommu_iova_free",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1613",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109968,
      "name": "vfio_iommu_iova_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void vfio_iommu_iova_free(struct list_head * iova)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void vfio_iommu_iova_free(struct list_head * iova)
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
void vfio_iommu_iova_free(struct list_head * iova)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void vfio_iommu_iova_free(struct list_head * iova)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void vfio_iommu_iova_free(struct list_head * iova)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void vfio_iommu_iova_free(struct list_head * iova)
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
void vfio_iommu_iova_free(struct list_head * iova)
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
