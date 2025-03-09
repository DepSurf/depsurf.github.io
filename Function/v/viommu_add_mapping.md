# Function: <code>viommu_add_mapping</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "viommu_add_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587426393,
      "name": "viommu_add_mapping",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:313",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_map"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int viommu_add_mapping(struct viommu_domain * vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags)
```

```json
{
  "name": "viommu_add_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588740016,
      "name": "viommu_add_mapping",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:314",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_map",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588740016,
      "name": "viommu_add_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int viommu_add_mapping(struct viommu_domain * vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags)
```

```json
{
  "name": "viommu_add_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590226032,
      "name": "viommu_add_mapping",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:313",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_map_pages",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590226032,
      "name": "viommu_add_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int viommu_add_mapping(struct viommu_domain * vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags)
```

```json
{
  "name": "viommu_add_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590546208,
      "name": "viommu_add_mapping",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:313",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_map_pages",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590546208,
      "name": "viommu_add_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
int viommu_add_mapping(struct viommu_domain * vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags)
```

```json
{
  "name": "viommu_add_mapping",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590902416,
      "name": "viommu_add_mapping",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:313",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_map_pages",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590902416,
      "name": "viommu_add_mapping",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "viommu_add_mapping",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498924480,
      "name": "viommu_add_mapping",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:314",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_map"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int viommu_add_mapping(struct viommu_domain * vdomain, u64 iova, u64 end, phys_addr_t paddr, u32 flags)
```
</details>
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
