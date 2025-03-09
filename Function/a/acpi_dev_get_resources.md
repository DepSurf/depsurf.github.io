# Function: <code>acpi_dev_get_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583571386,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:546",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_default_enumeration",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/spi/spi.c:acpi_spi_add_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571386,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583893676,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:584",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/i2c/i2c-core.c:acpi_i2c_get_info",
        "drivers/i2c/i2c-core.c:acpi_i2c_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893676,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584032790,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:600",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/i2c/i2c-core.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584032790,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584089104,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:600",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089104,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584360256,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:630",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360096,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581306,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:630",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581120,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584678666,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:630",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_acpi_add",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678512,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584878826,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584878672,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585014698,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014544,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585713569,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_dev_consumes_res"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715376,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585835681,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:615",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_dev_consumes_res"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585837488,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585715146,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:660",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716752,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586196474,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:667",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198304,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587433383,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:667",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_count_resources",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587435008,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588691255,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:784",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_count_resources",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588694512,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979159,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:825",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_count_resources",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588981872,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589282919,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:888",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_spi_device_alloc",
        "drivers/spi/spi.c:acpi_spi_count_resources",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285696,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497425780,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/pci/pci-acpi.c:acpi_get_rc_resources",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_ecam_init",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup",
        "drivers/perf/xgene_pmu.c:acpi_pmu_dev_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497425536,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584958058,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957904,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584866858,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584866704,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584966282,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966128,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```

```json
{
  "name": "acpi_dev_get_resources",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585072458,
      "name": "acpi_dev_get_resources",
      "external": true,
      "loc": "drivers/acpi/resource.c:622",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/pci_root.c:acpi_pci_probe_root_resources",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072304,
      "name": "acpi_dev_get_resources",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_dev_get_resources(struct acpi_device * adev, struct list_head * list, int (*)(struct acpi_resource *, void *) preproc, void * preproc_data)
```
</details>
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
