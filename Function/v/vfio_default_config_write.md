# Function: <code>vfio_default_config_write</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587079088,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071587086114,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922528,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071587930695,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983504,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071591535302,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865952,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071591477593,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_core_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471472,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071592551729,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_core_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589874368,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071594431065,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293413712,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293413712,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586727008,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071586734034,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033648,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071587040674,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```

```json
{
  "name": "vfio_default_config_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_write",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:200",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_vpd_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587140816,
      "name": "vfio_default_config_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071587147842,
      "name": "vfio_default_config_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device * vdev</code> ➡️ <code>struct vfio_pci_core_device * vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int vfio_default_config_write(struct vfio_pci_core_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
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
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
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
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
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
int vfio_default_config_write(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 val)
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
