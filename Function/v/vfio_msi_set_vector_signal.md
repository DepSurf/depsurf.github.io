# Function: <code>vfio_msi_set_vector_signal</code>

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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:284",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071136,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071587074913,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:288",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587913680,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
    },
    {
      "addr": 18446744071587917975,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:288",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587974848,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
    },
    {
      "addr": 18446744071591535220,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:288",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857248,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071591477511,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vfio_msi_set_vector_signal(struct vfio_pci_core_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:288",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461536,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071592550990,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vfio_msi_set_vector_signal(struct vfio_pci_core_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:288",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589864160,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071594430344,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293402832,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:284",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293402832,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:284",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719056,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071586722833,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:284",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025696,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071587029473,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```

```json
{
  "name": "vfio_msi_set_vector_signal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vfio_msi_set_vector_signal",
      "external": false,
      "loc": "drivers/vfio/pci/vfio_pci_intrs.c:284",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132864,
      "name": "vfio_msi_set_vector_signal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    },
    {
      "addr": 18446744071587136641,
      "name": "vfio_msi_set_vector_signal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
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
int vfio_msi_set_vector_signal(struct vfio_pci_core_device * vdev, int vector, int fd, bool msix)
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
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
int vfio_msi_set_vector_signal(struct vfio_pci_device * vdev, int vector, int fd, bool msix)
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
