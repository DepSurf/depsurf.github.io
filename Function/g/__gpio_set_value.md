# Function: <code>__gpio_set_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584595561,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:97",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584654046,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:97",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584696508,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:97",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585032564,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:97",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585633059,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:97",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:set_scl_gpio_value"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584943886,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585002543,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585044780,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585418564,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586031587,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:set_scl_gpio_value"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585127142,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler",
        "drivers/mfd/htc-i2cpld.c:htcpld_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185999,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585228604,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585619496,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586229459,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:set_scl_gpio_value"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585208560,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585268194,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310284,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585703288,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586313683,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:101",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585636731,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585696290,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585738620,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586135435,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586776371,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:set_scl_gpio_value"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585881122,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585942415,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585983980,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586383819,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_set_cs"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586016898,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586078591,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586121388,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_remove",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524844,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_set_cs"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586260404,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586313602,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586356505,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586408628,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461778,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586504521,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __gpio_set_value(unsigned int gpio, int value)
```

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587183952,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    },
    {
      "addr": 18446744071587237580,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587283337,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587183952,
      "name": "__gpio_set_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __gpio_set_value(unsigned int gpio, int value)
```

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587264944,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    },
    {
      "addr": 18446744071587307036,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587345609,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264944,
      "name": "__gpio_set_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __gpio_set_value(unsigned int gpio, int value)
```

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587153280,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    },
    {
      "addr": 18446744071587194932,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587228665,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153280,
      "name": "__gpio_set_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __gpio_set_value(unsigned int gpio, int value)
```

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587729760,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    },
    {
      "addr": 18446744071587756857,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587793790,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587729760,
      "name": "__gpio_set_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void __gpio_set_value(unsigned int gpio, int value)
```

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589074672,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ]
    },
    {
      "addr": 18446744071589101854,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589141756,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:100",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589074672,
      "name": "__gpio_set_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590688780,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:78",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499257940,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499329800,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499381816,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243346688,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "arch/arm/mach-omap2/pdata-quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231313488,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/tty/serial/omap-serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/omap-serial.c:serial_omap_config_rs485",
        "drivers/tty/serial/omap-serial.c:serial_omap_start_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_tx"
      ],
      "caller_func": []
    },
    {
      "addr": 3231775960,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231879732,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 3231935104,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292443740,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292549700,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292619228,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276516896,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276575900,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276617222,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586356596,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409746,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586452489,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
  "name": "__gpio_set_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586468276,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/htc-i2cpld.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586521426,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/twl6040.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power",
        "drivers/mfd/twl6040.c:twl6040_power"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586564169,
      "name": "__gpio_set_value",
      "external": false,
      "loc": "include/asm-generic/gpio.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:aat2870_i2c_resume",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_suspend",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe",
        "drivers/mfd/aat2870-core.c:aat2870_i2c_probe"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __gpio_set_value(unsigned int gpio, int value)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __gpio_set_value(unsigned int gpio, int value)
```
</details>
</li>
</ul>
