# Function: <code>pci_alloc_irq_vectors</code>

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
int pci_alloc_irq_vectors(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags)
```

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583700384,
      "name": "pci_alloc_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi.c:1185",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583700384,
      "name": "pci_alloc_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584347254,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1390",
      "file": "drivers/virtio/virtio_pci_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583830045,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1395",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586120452,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1395",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584093261,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1420",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563268,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1420",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584285603,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1418",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586827972,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1418",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584381027,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1452",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586984612,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1452",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584577893,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1521",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587243247,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1521",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584714981,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872738,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587073777,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587435356,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585369241,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1799",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586605741,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1799",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587915707,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1799",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588296734,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1799",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585527721,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1807",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586716141,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1807",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587976875,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1807",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588138188,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1807",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588330894,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1807",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585405849,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1823",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599760,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1823",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587859276,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1823",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588020284,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1823",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588213577,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1823",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585867809,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1886",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587142285,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1886",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588463964,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1886",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588636353,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1886",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855561,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1886",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587062141,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1905",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451380,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1905",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589866387,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1905",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590052475,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1905",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590281456,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1905",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags)
```

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588234176,
      "name": "pci_alloc_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi/api.c:234",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588234176,
      "name": "pci_alloc_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int pci_alloc_irq_vectors(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags)
```

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588509680,
      "name": "pci_alloc_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi/api.c:234",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588509680,
      "name": "pci_alloc_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int pci_alloc_irq_vectors(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags)
```

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588808272,
      "name": "pci_alloc_irq_vectors",
      "external": true,
      "loc": "drivers/pci/msi/api.c:234",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/tty/serial/8250/8250_mid.c:dnv_setup",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588808272,
      "name": "pci_alloc_irq_vectors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496973740,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498607820,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500566116,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230237992,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3231238308,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 3233029876,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291829156,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293406880,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293966608,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275642166,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276206426,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277441778,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584665461,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585633730,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586515527,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587141436,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584594613,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585498802,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384103,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721697,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586900044,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584665141,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585823138,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587028337,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587389916,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_alloc_irq_vectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584772837,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585930754,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587135505,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/vfio/pci/vfio_pci_intrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_msi_trigger"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587496124,
      "name": "pci_alloc_irq_vectors",
      "external": false,
      "loc": "include/linux/pci.h:1776",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int pci_alloc_irq_vectors(struct pci_dev * dev, unsigned int min_vecs, unsigned int max_vecs, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
