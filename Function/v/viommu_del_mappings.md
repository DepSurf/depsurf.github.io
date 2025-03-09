# Function: <code>viommu_del_mappings</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
size_t viommu_del_mappings(struct viommu_domain * vdomain, long unsigned int iova, size_t size)
```

```json
{
  "name": "viommu_del_mappings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587424560,
      "name": "viommu_del_mappings",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:345",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_unmap",
        "drivers/iommu/virtio-iommu.c:viommu_map",
        "drivers/iommu/virtio-iommu.c:viommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424560,
      "name": "viommu_del_mappings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
size_t viommu_del_mappings(struct viommu_domain * vdomain, u64 iova, u64 end)
```

```json
{
  "name": "viommu_del_mappings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588737504,
      "name": "viommu_del_mappings",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:345",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_unmap",
        "drivers/iommu/virtio-iommu.c:viommu_map",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588737504,
      "name": "viommu_del_mappings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
size_t viommu_del_mappings(struct viommu_domain * vdomain, u64 iova, u64 end)
```

```json
{
  "name": "viommu_del_mappings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590223040,
      "name": "viommu_del_mappings",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:344",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_unmap_pages",
        "drivers/iommu/virtio-iommu.c:viommu_map_pages",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590223040,
      "name": "viommu_del_mappings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
size_t viommu_del_mappings(struct viommu_domain * vdomain, u64 iova, u64 end)
```

```json
{
  "name": "viommu_del_mappings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590542912,
      "name": "viommu_del_mappings",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:344",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_unmap_pages",
        "drivers/iommu/virtio-iommu.c:viommu_map_pages",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590542912,
      "name": "viommu_del_mappings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
size_t viommu_del_mappings(struct viommu_domain * vdomain, u64 iova, u64 end)
```

```json
{
  "name": "viommu_del_mappings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590898944,
      "name": "viommu_del_mappings",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:344",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_unmap_pages",
        "drivers/iommu/virtio-iommu.c:viommu_map_pages",
        "drivers/iommu/virtio-iommu.c:viommu_attach_dev",
        "drivers/iommu/virtio-iommu.c:viommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590898944,
      "name": "viommu_del_mappings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t viommu_del_mappings(struct viommu_domain * vdomain, long unsigned int iova, size_t size)
```

```json
{
  "name": "viommu_del_mappings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498922744,
      "name": "viommu_del_mappings",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:346",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_unmap",
        "drivers/iommu/virtio-iommu.c:viommu_map",
        "drivers/iommu/virtio-iommu.c:viommu_domain_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498922744,
      "name": "viommu_del_mappings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    }
  ]
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
size_t viommu_del_mappings(struct viommu_domain * vdomain, long unsigned int iova, size_t size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 end</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int iova</code> ➡️ <code>u64 iova</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
size_t viommu_del_mappings(struct viommu_domain * vdomain, long unsigned int iova, size_t size)
```
</details>
</li>
</ul>
