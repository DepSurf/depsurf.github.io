# Function: <code>iommu_sva_unbind_gpasid</code>

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
int iommu_sva_unbind_gpasid(struct iommu_domain * domain, struct device * dev, ioasid_t pasid)
```

```json
{
  "name": "iommu_sva_unbind_gpasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586762992,
      "name": "iommu_sva_unbind_gpasid",
      "external": true,
      "loc": "drivers/iommu/iommu.c:1973",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762992,
      "name": "iommu_sva_unbind_gpasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iommu_sva_unbind_gpasid(struct iommu_domain * domain, struct device * dev, ioasid_t pasid)
```

```json
{
  "name": "iommu_sva_unbind_gpasid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944246,
      "name": "iommu_sva_unbind_gpasid",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2166",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_uapi_sva_unbind_gpasid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941616,
      "name": "iommu_sva_unbind_gpasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iommu_sva_unbind_gpasid(struct iommu_domain * domain, struct device * dev, ioasid_t pasid)
```

```json
{
  "name": "iommu_sva_unbind_gpasid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586825989,
      "name": "iommu_sva_unbind_gpasid",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2197",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_uapi_sva_unbind_gpasid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823456,
      "name": "iommu_sva_unbind_gpasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int iommu_sva_unbind_gpasid(struct iommu_domain * domain, struct device * dev, ioasid_t pasid)
```

```json
{
  "name": "iommu_sva_unbind_gpasid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587386437,
      "name": "iommu_sva_unbind_gpasid",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2218",
      "file": "drivers/iommu/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu.c:iommu_uapi_sva_unbind_gpasid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383536,
      "name": "iommu_sva_unbind_gpasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
int iommu_sva_unbind_gpasid(struct iommu_domain * domain, struct device * dev, ioasid_t pasid)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int iommu_sva_unbind_gpasid(struct iommu_domain * domain, struct device * dev, ioasid_t pasid)
```
</details>
</li>
</ul>
