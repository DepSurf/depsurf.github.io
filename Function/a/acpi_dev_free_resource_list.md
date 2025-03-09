# Function: <code>acpi_dev_free_resource_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583570223,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:452",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_default_enumeration",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446744071583570223,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583892517,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:490",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/i2c/i2c-core.c:acpi_i2c_get_info",
        "drivers/i2c/i2c-core.c:acpi_i2c_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892517,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584033189,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:506",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init",
        "drivers/i2c/i2c-core.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031631,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584089535,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:506",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584087280,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584360374,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:507",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358048,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581398,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:507",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446744071584579056,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584678758,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:507",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446744071584676432,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584878918,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446744071584876704,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585014790,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446744071585012576,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585713667,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_dev_consumes_res",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071585712816,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585835779,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:492",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_dev_consumes_res",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_device_enumeration_by_parent",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071585834928,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585715230,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:537",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071585714224,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586196558,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:544",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071586195552,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587433473,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:544",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071587432800,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588691345,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:661",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071588690624,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979249,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:702",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071588978528,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589283009,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:765",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb",
        "drivers/acpi/resource.c:acpi_dev_get_memory_resources",
        "drivers/acpi/resource.c:acpi_dev_get_dma_resources"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/acpi/acpi_platform.c:acpi_create_platform_device",
        "drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
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
      "addr": 18446744071589282288,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497425884,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe",
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe",
        "drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/pci/pci-acpi.c:acpi_get_rc_resources",
        "drivers/pci/controller/pci-xgene.c:xgene_pcie_ecam_init",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446603336497423216,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584958150,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584955936,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584866950,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/char/tpm/tpm_crb.c:crb_map_io",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864736,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584966374,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446744071584964160,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```

```json
{
  "name": "acpi_dev_free_resource_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585072550,
      "name": "acpi_dev_free_resource_list",
      "external": true,
      "loc": "drivers/acpi/resource.c:499",
      "file": "drivers/acpi/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/resource.c:acpi_res_consumer_cb"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_dma_get_range",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_create_device",
        "drivers/acpi/acpi_apd.c:st_misc_setup",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
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
      "addr": 18446744071585070336,
      "name": "acpi_dev_free_resource_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void acpi_dev_free_resource_list(struct list_head * list)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_dev_free_resource_list(struct list_head * list)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_dev_free_resource_list(struct list_head * list)
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
