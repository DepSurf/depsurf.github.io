# Function: <code>acpi_dev_gpio_irq_wake_get_by</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_dev_gpio_irq_wake_get_by(struct acpi_device * adev, const char * name, int index, bool * wake_capable)
```

```json
{
  "name": "acpi_dev_gpio_irq_wake_get_by",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_dev_gpio_irq_wake_get_by",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1049",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596206373,
      "name": "acpi_dev_gpio_irq_wake_get_by.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071588063248,
      "name": "acpi_dev_gpio_irq_wake_get_by",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_dev_gpio_irq_wake_get_by(struct acpi_device * adev, const char * name, int index, bool * wake_capable)
```

```json
{
  "name": "acpi_dev_gpio_irq_wake_get_by",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_dev_gpio_irq_wake_get_by",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1051",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596731427,
      "name": "acpi_dev_gpio_irq_wake_get_by.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588337840,
      "name": "acpi_dev_gpio_irq_wake_get_by",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_dev_gpio_irq_wake_get_by(struct acpi_device * adev, const char * name, int index, bool * wake_capable)
```

```json
{
  "name": "acpi_dev_gpio_irq_wake_get_by",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_dev_gpio_irq_wake_get_by",
      "external": true,
      "loc": "drivers/gpio/gpiolib-acpi.c:1028",
      "file": "drivers/gpio/gpiolib-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:ec_install_handlers",
        "drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource",
        "drivers/base/platform.c:platform_get_irq_optional",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597639775,
      "name": "acpi_dev_gpio_irq_wake_get_by.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588632080,
      "name": "acpi_dev_gpio_irq_wake_get_by",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int acpi_dev_gpio_irq_wake_get_by(struct acpi_device * adev, const char * name, int index, bool * wake_capable)
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
