# Function: <code>__devm_request_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397200,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1356",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397200,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409552,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1425",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409552,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429856,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1425",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429856,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417504,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1425",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417504,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445536,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1443",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_devmem_add",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445536,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460320,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1413",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_devmem_add",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460320,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493968,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1423",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hmm.c:hmm_devmem_add",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493968,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511808,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_request_free_mem_region",
        "lib/devres.c:devm_ioremap_resource",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511808,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537872,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537872,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567808,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1451",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567808,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549152,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1524",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_free_mem_region",
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549152,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554720,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1577",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554720,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627280,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1577",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627280,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579721344,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1564",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721344,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849136,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1556",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849136,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899376,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1556",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899376,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938112,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1611",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938112,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490684208,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/bus/fsl-mc/mc-io.c:fsl_create_mc_io",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_request_port",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/net/ethernet/freescale/fman/fman.c:read_dts_node",
        "drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/edac/altera_edac.c:altr_edac_device_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490684208,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224752756,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/tty/serial/owl-uart.c:owl_uart_request_port",
        "drivers/tty/serial/rda-uart.c:rda_uart_request_port",
        "drivers/misc/sram.c:sram_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224752756,
      "name": "__devm_request_region",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283508368,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283508368,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271417956,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/pinctrl/pinctrl-single.c:pcs_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271417956,
      "name": "__devm_request_region",
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511536,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511536,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440336,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/dax/device.c:dev_dax_probe",
        "drivers/dax/pmem/core.c:__dax_pmem_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440336,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511456,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511456,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct resource * __devm_request_region(struct device * dev, struct resource * parent, resource_size_t start, resource_size_t n, const char * name)
```

```json
{
  "name": "__devm_request_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544352,
      "name": "__devm_request_region",
      "external": true,
      "loc": "kernel/resource.c:1446",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe",
        "drivers/pci/pci.c:devm_pci_remap_cfg_resource",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/misc/sram.c:sram_probe",
        "drivers/nvdimm/claim.c:devm_nsio_enable",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544352,
      "name": "__devm_request_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
