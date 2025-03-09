# Function: <code>synchronize_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741056,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:104",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741056,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763088,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:104",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763088,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579790048,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:104",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790048,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787744,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:106",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787744,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821184,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:106",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821184,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854960,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:106",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854960,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901920,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:106",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901920,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936672,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936672,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579986800,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986800,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046512,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:133",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046512,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029712,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:133",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_remove_irq",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029712,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030448,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:133",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030448,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162960,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:126",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162960,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309088,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:126",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ohci-hcd.c:ohci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309088,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521872,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:126",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ohci-hcd.c:ohci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521872,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580594800,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:126",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ohci-hcd.c:ohci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594800,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580660522,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:136",
      "file": "kernel/irq/manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:disable_irq"
      ],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_dispose_mapping",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_mmio.c:vm_synchronize_cbs",
        "drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/platform.c:dwc2_driver_shutdown",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/ohci-hcd.c:ohci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659616,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491177640,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491177640,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225199500,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225199500,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284075552,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/hvc/hvsi.c:hvsi_close",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284075552,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271725890,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:hcd_pci_runtime_suspend",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271725890,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955536,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955536,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893392,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893392,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947072,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947072,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void synchronize_irq(unsigned int irq)
```

```json
{
  "name": "synchronize_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993504,
      "name": "synchronize_irq",
      "external": true,
      "loc": "kernel/irq/manage.c:132",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:disable_irq",
        "kernel/irq/irqdomain.c:irq_domain_free_irqs",
        "kernel/irq/irqdomain.c:irq_domain_disassociate",
        "kernel/irq/pm.c:suspend_device_irqs",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors",
        "drivers/tty/serial/serial_core.c:uart_port_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop",
        "drivers/usb/host/ehci-hcd.c:ehci_suspend",
        "drivers/usb/host/ehci-hcd.c:ehci_halt",
        "drivers/usb/host/uhci-hcd.c:uhci_pci_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/input/serio/i8042.c:i8042_stop",
        "drivers/input/serio/i8042.c:i8042_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993504,
      "name": "synchronize_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
