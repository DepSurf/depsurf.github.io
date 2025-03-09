# Function: <code>dev_iommu_priv_set</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_iommu_priv_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586807353,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:639",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
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
  "name": "dev_iommu_priv_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586866734,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:625",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586912800,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:625",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
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
  "name": "dev_iommu_priv_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586749342,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:586",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586793312,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:586",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
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
  "name": "dev_iommu_priv_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587302878,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:663",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587350160,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:663",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587427313,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:663",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe_device"
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
  "name": "dev_iommu_priv_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588616159,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:655",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:amd_iommu_release_device",
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659296,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:655",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742594,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:655",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe_device"
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
  "name": "dev_iommu_priv_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590073345,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:698",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590127477,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:698",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590228946,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:698",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe_device"
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
  "name": "dev_iommu_priv_set",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590384977,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:701",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:iommu_init_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590440917,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:701",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590549138,
      "name": "dev_iommu_priv_set",
      "external": false,
      "loc": "include/linux/iommu.h:701",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe_device"
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
void dev_iommu_priv_set(struct device * dev, void * priv)
```

```json
{
  "name": "dev_iommu_priv_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590846880,
      "name": "dev_iommu_priv_set",
      "external": true,
      "loc": "drivers/iommu/iommu.c:390",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device",
        "drivers/iommu/virtio-iommu.c:viommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590846880,
      "name": "dev_iommu_priv_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void dev_iommu_priv_set(struct device * dev, void * priv)
```
</details>
</li>
</ul>
