# Function: <code>vfio_iommu_unmap_unpin_all</code>

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
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```

```json
{
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587053232,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1854",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587053232,
      "name": "vfio_iommu_unmap_unpin_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587885465,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2214",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
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
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587947009,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2234",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
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
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587829217,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2448",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
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
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588434657,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2450",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
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
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589834824,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:2446",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
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
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```

```json
{
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701152,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1854",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701152,
      "name": "vfio_iommu_unmap_unpin_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```

```json
{
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587007792,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1854",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587007792,
      "name": "vfio_iommu_unmap_unpin_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```

```json
{
  "name": "vfio_iommu_unmap_unpin_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587114960,
      "name": "vfio_iommu_unmap_unpin_all",
      "external": false,
      "loc": "drivers/vfio/vfio_iommu_type1.c:1854",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114960,
      "name": "vfio_iommu_unmap_unpin_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
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
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
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
void vfio_iommu_unmap_unpin_all(struct vfio_iommu * iommu)
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
