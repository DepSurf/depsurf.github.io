# Function: <code>pci_irq_vector</code>

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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695136,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1231",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695136,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833248,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1265",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833248,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583875520,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1209",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875520,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138992,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1209",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138992,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355472,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1208",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355472,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584450544,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1228",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450544,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647456,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1257",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647456,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584786096,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786096,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476928,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476928,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585517168,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1278",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517168,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585395728,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1284",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395728,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585858368,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1199",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858368,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587052942,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:1070",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pci_irq_get_affinity",
        "drivers/pci/msi/msi.c:pci_irq_get_affinity"
      ],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052832,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588235150,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi/api.c:313",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/api.c:pci_irq_get_affinity",
        "drivers/pci/msi/api.c:pci_irq_get_affinity"
      ],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588234768,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588510654,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi/api.c:313",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/api.c:pci_irq_get_affinity",
        "drivers/pci/msi/api.c:pci_irq_get_affinity"
      ],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588510272,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588809246,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi/api.c:313",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/api.c:pci_irq_get_affinity",
        "drivers/pci/msi/api.c:pci_irq_get_affinity"
      ],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_request_msix_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588808864,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497051464,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497051464,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230261988,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230261988,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291088928,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291088928,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275698962,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275698962,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584734848,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734848,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584665616,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/nvme/host/pci.c:nvme_poll_irqdisable",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665616,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584736256,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736256,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
```

```json
{
  "name": "pci_irq_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584843824,
      "name": "pci_irq_vector",
      "external": true,
      "loc": "drivers/pci/msi.c:1258",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/irq.c:pci_free_irq",
        "drivers/pci/irq.c:pci_request_irq",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_del_vqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843824,
      "name": "pci_irq_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int pci_irq_vector(struct pci_dev * dev, unsigned int nr)
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
