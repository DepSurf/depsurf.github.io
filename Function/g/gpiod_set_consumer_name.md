# Function: <code>gpiod_set_consumer_name</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199104,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3373",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199104,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387616,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3462",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387616,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523840,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523840,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4222",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221028,
      "name": "gpiod_set_consumer_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585204512,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3046",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387661,
      "name": "gpiod_set_consumer_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585361168,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3023",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591329971,
      "name": "gpiod_set_consumer_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585244720,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3072",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592352856,
      "name": "gpiod_set_consumer_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071585700400,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3193",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214597,
      "name": "gpiod_set_consumer_name.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071586867616,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588014880,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3263",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588014880,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289712,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3304",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289712,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588583408,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3497",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/twl6040.c:twl6040_probe",
        "drivers/spi/spi.c:spi_get_gpio_descs",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588583408,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496700752,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496700752,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229997604,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/sata_highbank.c:ahci_highbank_probe",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229997604,
      "name": "gpiod_set_consumer_name",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290790848,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290790848,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275467304,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275467304,
      "name": "gpiod_set_consumer_name",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584480768,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480768,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418896,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418896,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584475504,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475504,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```

```json
{
  "name": "gpiod_set_consumer_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581632,
      "name": "gpiod_set_consumer_name",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3816",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/phy/mdio_bus.c:mdiobus_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581632,
      "name": "gpiod_set_consumer_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int gpiod_set_consumer_name(struct gpio_desc * desc, const char * name)
```
</details>
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
