# Function: <code>pci_disable_msix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583388400,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1002",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/virtio/virtio_pci_common.c:vp_free_vectors",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388400,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583702816,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1015",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/virtio/virtio_pci_common.c:vp_free_vectors",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583702816,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583841136,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1035",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/portdrv_core.c:cleanup_service_irqs",
        "drivers/pci/msi.c:pci_free_irq_vectors",
        "drivers/usb/host/xhci.c:xhci_cleanup_msix",
        "drivers/usb/host/xhci.c:xhci_setup_msix"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841136,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583879648,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:995",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879648,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584143136,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:995",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143136,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584359952,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:995",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584359952,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584455104,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:993",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455104,
      "name": "pci_disable_msix",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584651904,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1028",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584651904,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584788144,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788144,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585483488,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483488,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585519808,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1053",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519808,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585399376,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1059",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399376,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585863504,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:967",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585863504,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587057324,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:845",
      "file": "drivers/pci/msi/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/msi/msi.c:pcim_msi_release"
      ],
      "caller_func": [
        "drivers/pci/msi/msi.c:pcim_msi_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587056752,
      "name": "pci_disable_msix.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    },
    {
      "addr": 18446744071587057120,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588234624,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi/api.c:194",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588234624,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588510128,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi/api.c:194",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588510128,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588808720,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi/api.c:194",
      "file": "drivers/pci/msi/api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/msi/api.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588808720,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497055208,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497055208,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230268888,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230268888,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291097472,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291097472,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275704866,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275704866,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584736896,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736896,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584667664,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584667664,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584738304,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738304,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void pci_disable_msix(struct pci_dev * dev)
```

```json
{
  "name": "pci_disable_msix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584845872,
      "name": "pci_disable_msix",
      "external": true,
      "loc": "drivers/pci/msi.c:1029",
      "file": "drivers/pci/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pcim_release",
        "drivers/pci/msi.c:pci_free_irq_vectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845872,
      "name": "pci_disable_msix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
