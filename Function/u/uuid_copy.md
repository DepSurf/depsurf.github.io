# Function: <code>uuid_copy</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:63",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:63",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:64",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:64",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uuid_copy(uuid_t * dst, const uuid_t * src)
```

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904043,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:66",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900704,
      "name": "uuid_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void uuid_copy(uuid_t * dst, const uuid_t * src)
```

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587965442,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:66",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961280,
      "name": "uuid_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void uuid_copy(uuid_t * dst, const uuid_t * src)
```

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587847364,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:66",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_validate_vf_token"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843472,
      "name": "uuid_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void uuid_copy(uuid_t * dst, const uuid_t * src)
```

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588453476,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:66",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token"
      ],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448752,
      "name": "uuid_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589855263,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:66",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_validate_vf_token",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl_feature"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229274808,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_ldmdb_add"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290146756,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_ldmdb_add"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275045192,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_ldmdb_add"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586468285,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_report_ns_ids"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586344525,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_report_ns_ids"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uuid_copy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "uuid_copy",
      "external": false,
      "loc": "include/linux/uuid.h:56",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void uuid_copy(uuid_t * dst, const uuid_t * src)
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
void uuid_copy(uuid_t * dst, const uuid_t * src)
```
</details>
</li>
</ul>
