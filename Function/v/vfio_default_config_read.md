# Function: <code>vfio_default_config_read</code>

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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078000,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071587086102,
      "name": "vfio_default_config_read.cold",
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922224,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071587930683,
      "name": "vfio_default_config_read.cold",
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983200,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071591535290,
      "name": "vfio_default_config_read.cold",
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587865648,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071591477581,
      "name": "vfio_default_config_read.cold",
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
int vfio_default_config_read(struct vfio_pci_core_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588471840,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071592551741,
      "name": "vfio_default_config_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int vfio_default_config_read(struct vfio_pci_core_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589874784,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071594431077,
      "name": "vfio_default_config_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293412848,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293412848,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725920,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071586734022,
      "name": "vfio_default_config_read.cold",
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032560,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071587040662,
      "name": "vfio_default_config_read.cold",
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```

```json
{
  "name": "vfio_default_config_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_default_config_read",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_config.c:174",
      "file": "drivers/vfio/pci/vfio_pci_config.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_config.c:vfio_msi_config_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139728,
      "name": "vfio_default_config_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071587147830,
      "name": "vfio_default_config_read.cold",
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
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
int vfio_default_config_read(struct vfio_pci_core_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
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
int vfio_default_config_read(struct vfio_pci_device * vdev, int pos, int count, struct perm_bits * perm, int offset, __le32 * val)
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
