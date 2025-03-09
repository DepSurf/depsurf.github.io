# Function: <code>pci_alloc_irq_vectors_affinity</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583838496,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1199",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583838496,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880736,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1151",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880736,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144224,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1151",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144224,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361040,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1150",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361040,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456224,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1166",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456224,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1188",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655774,
      "name": "pci_alloc_irq_vectors_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071584652992,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584791152,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584791152,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585483104,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483104,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523232,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1213",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523232,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585401408,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1219",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585401408,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1127",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592369096,
      "name": "pci_alloc_irq_vectors_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585862848,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587056464,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:998",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587056464,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588233872,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi/api.c:254",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233872,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588509376,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi/api.c:254",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588509376,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588807968,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi/api.c:254",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_alloc_irq_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807968,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497058816,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497058816,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230268536,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230268536,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291096976,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291096976,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275704626,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275704626,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739904,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739904,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584670672,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584670672,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584741312,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584741312,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, struct irq_affinity * affd)
```

```json
{
  "name": "pci_alloc_irq_vectors_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584848880,
      "name": "pci_alloc_irq_vectors_affinity",
      "external": true,
      "loc": "drivers/pci/msi.c:1189",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584848880,
      "name": "pci_alloc_irq_vectors_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int pci_alloc_irq_vectors_affinity(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags, const struct irq_affinity * affd)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct irq_affinity * affd</code> ➡️ <code>struct irq_affinity * affd</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
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
