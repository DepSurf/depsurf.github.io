# Function: <code>vfio_info_cap_add</code>

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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039280,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1817",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039280,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869296,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1837",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869296,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929728,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1838",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929728,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587811872,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1737",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587811872,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588414288,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1844",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414288,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589815184,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1808",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589815184,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293369424,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1817",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293369424,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586687200,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1817",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586687200,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586993840,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1817",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993840,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```

```json
{
  "name": "vfio_info_cap_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587101008,
      "name": "vfio_info_cap_add",
      "external": true,
      "loc": "drivers/vfio/vfio.c:1817",
      "file": "drivers/vfio/vfio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio.c:vfio_info_add_capability",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_build_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101008,
      "name": "vfio_info_cap_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
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
struct vfio_info_cap_header * vfio_info_cap_add(struct vfio_info_cap * caps, size_t size, u16 id, u16 version)
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
