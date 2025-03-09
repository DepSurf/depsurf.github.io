# Function: <code>pci_free_irq_vectors</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583702880,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1219",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702880,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841200,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1253",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841200,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583881328,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1197",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881328,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144816,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1197",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144816,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361616,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1196",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361616,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456768,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1216",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456768,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584653616,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1245",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653616,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789536,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789536,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585483792,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483792,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585522096,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1266",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522096,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585400112,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1272",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585400112,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585863808,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1180",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585863808,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587057324,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:1051",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pcim_msi_release"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587057184,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588235328,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi/api.c:426",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:pcim_msi_release",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588235328,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588510832,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi/api.c:426",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:pcim_msi_release",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588510832,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588809424,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi/api.c:426",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/msi.c:pcim_msi_release",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809424,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497056704,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497056704,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230269192,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230269192,
      "name": "pci_free_irq_vectors",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291097872,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291097872,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275705100,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275705100,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584738288,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738288,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669056,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/nvme/host/pci.c:nvme_dev_disable",
        "drivers/nvme/host/pci.c:nvme_setup_io_queues",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669056,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739696,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739696,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_free_irq_vectors(struct pci_dev * dev)
```

```json
{
  "name": "pci_free_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584847264,
      "name": "pci_free_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1246",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_remove",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847264,
      "name": "pci_free_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void pci_free_irq_vectors(struct pci_dev * dev)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
