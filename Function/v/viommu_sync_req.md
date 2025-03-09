# Function: <code>viommu_sync_req</code>

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
  "name": "viommu_sync_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587426098,
      "name": "viommu_sync_req",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:187",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_iotlb_sync"
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
  "name": "viommu_sync_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588739922,
      "name": "viommu_sync_req",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:188",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_iotlb_sync"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "viommu_sync_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590225922,
      "name": "viommu_sync_req",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:187",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_iotlb_sync"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "viommu_sync_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590546098,
      "name": "viommu_sync_req",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:187",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_iotlb_sync"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int viommu_sync_req(struct viommu_dev * viommu)
```

```json
{
  "name": "viommu_sync_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590900064,
      "name": "viommu_sync_req",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:187",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/virtio-iommu.c:viommu_iotlb_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590900064,
      "name": "viommu_sync_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
  "name": "viommu_sync_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498920852,
      "name": "viommu_sync_req",
      "external": false,
      "loc": "drivers/iommu/virtio-iommu.c:188",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_iotlb_sync"
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int viommu_sync_req(struct viommu_dev * viommu)
```
</details>
</li>
</ul>
