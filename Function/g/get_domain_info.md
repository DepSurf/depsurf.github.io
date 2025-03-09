# Function: <code>get_domain_info</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct device_domain_info * get_domain_info(struct device * dev)
```

```json
{
  "name": "get_domain_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586846789,
      "name": "get_domain_info",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:369",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_detach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:auxiliary_unlink_device",
        "drivers/iommu/intel/iommu.c:bounce_unmap_single",
        "drivers/iommu/intel/iommu.c:bounce_map_single",
        "drivers/iommu/intel/iommu.c:bounce_sync_single",
        "drivers/iommu/intel/iommu.c:intel_map_sg",
        "drivers/iommu/intel/iommu.c:intel_unmap",
        "drivers/iommu/intel/iommu.c:__intel_map_single"
      ],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_free_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855648,
      "name": "get_domain_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct device_domain_info * get_domain_info(struct device * dev)
```

```json
{
  "name": "get_domain_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586902021,
      "name": "get_domain_info",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:366",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_remove_dev",
        "drivers/iommu/intel/iommu.c:aux_domain_remove_dev",
        "drivers/iommu/intel/iommu.c:auxiliary_unlink_device",
        "drivers/iommu/intel/iommu.c:auxiliary_link_device",
        "drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:domain_update_iotlb"
      ],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_free_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908688,
      "name": "get_domain_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
struct device_domain_info * get_domain_info(struct device * dev)
```

```json
{
  "name": "get_domain_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586781125,
      "name": "get_domain_info",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:375",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:auxiliary_unlink_device",
        "drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:domain_update_iotlb"
      ],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_free_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586788528,
      "name": "get_domain_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct device_domain_info * get_domain_info(struct device * dev)
```

```json
{
  "name": "get_domain_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587335653,
      "name": "get_domain_info",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:357",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat",
        "drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:auxiliary_unlink_device",
        "drivers/iommu/intel/iommu.c:dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:domain_update_iotlb"
      ],
      "caller_func": [
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_get_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_free_table",
        "drivers/iommu/intel/pasid.c:intel_pasid_alloc_table",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587345104,
      "name": "get_domain_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
struct device_domain_info * get_domain_info(struct device * dev)
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
struct device_domain_info * get_domain_info(struct device * dev)
```
</details>
</li>
</ul>
