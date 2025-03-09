# Function: <code>__iommu_group_set_domain</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __iommu_group_set_domain(struct iommu_group * group, struct iommu_domain * new_domain)
```

```json
{
  "name": "__iommu_group_set_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588705616,
      "name": "__iommu_group_set_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2122",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_group_release_dma_owner",
        "drivers/iommu/iommu.c:iommu_group_claim_dma_owner",
        "drivers/iommu/iommu.c:iommu_detach_group",
        "drivers/iommu/iommu.c:iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588705616,
      "name": "__iommu_group_set_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int __iommu_group_set_domain(struct iommu_group * group, struct iommu_domain * new_domain)
```

```json
{
  "name": "__iommu_group_set_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590184256,
      "name": "__iommu_group_set_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2186",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_release_dma_ownership",
        "drivers/iommu/iommu.c:iommu_detach_group",
        "drivers/iommu/iommu.c:__iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_detach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590184256,
      "name": "__iommu_group_set_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
  "name": "__iommu_group_set_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590511711,
      "name": "__iommu_group_set_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:114",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_setup_default_domain",
        "drivers/iommu/iommu.c:iommu_attach_group",
        "drivers/iommu/iommu.c:iommu_attach_device"
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
  "name": "__iommu_group_set_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590866318,
      "name": "__iommu_group_set_domain",
      "external": false,
      "loc": "drivers/iommu/iommu.c:116",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_setup_default_domain",
        "drivers/iommu/iommu.c:iommu_group_replace_domain",
        "drivers/iommu/iommu.c:__iommu_attach_group"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int __iommu_group_set_domain(struct iommu_group * group, struct iommu_domain * new_domain)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __iommu_group_set_domain(struct iommu_group * group, struct iommu_domain * new_domain)
```
</details>
</li>
</ul>
