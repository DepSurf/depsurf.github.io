# Function: <code>mctrl_gpio_get_outputs</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585749056,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:89",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749056,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891280,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891280,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586628752,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586628752,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586738096,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738096,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586621728,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621728,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587167696,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587167696,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588478960,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588478960,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589913616,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:118",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589913616,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590222784,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:118",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590222784,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590563504,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:118",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_irq",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590563504,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498707432,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498707432,
      "name": "mctrl_gpio_get_outputs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231336676,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231336676,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291857200,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291857200,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276227496,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276227496,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585652272,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585652272,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585517344,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517344,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585841680,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841680,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```

```json
{
  "name": "mctrl_gpio_get_outputs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585949296,
      "name": "mctrl_gpio_get_outputs",
      "external": true,
      "loc": "drivers/tty/serial/serial_mctrl_gpio.c:97",
      "file": "drivers/tty/serial/serial_mctrl_gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_config_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_start_tx",
        "drivers/tty/serial/8250/8250_port.c:autoconfig",
        "drivers/tty/serial/8250/8250_port.c:autoconfig_16550a",
        "drivers/tty/serial/8250/8250_port.c:size_fifo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585949296,
      "name": "mctrl_gpio_get_outputs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios * gpios, unsigned int * mctrl)
```
</details>
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
