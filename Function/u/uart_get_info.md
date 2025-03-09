# Function: <code>uart_get_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584089184,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:708",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089184,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584419824,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:731",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584419824,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584602240,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:723",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602240,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684704,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:724",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684704,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585096912,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:732",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585096912,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585330848,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:739",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330848,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454112,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:759",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454112,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670000,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:753",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670000,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810944,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810944,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586541616,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:755",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586541616,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652592,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:756",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652592,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586536560,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:756",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586536560,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074976,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:739",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074976,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588378960,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:751",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378960,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589803088,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:757",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803088,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590108048,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:778",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590108048,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590447584,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:769",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:iomem_reg_shift_show",
        "drivers/tty/serial/serial_core.c:iomem_base_show",
        "drivers/tty/serial/serial_core.c:io_type_show",
        "drivers/tty/serial/serial_core.c:custom_divisor_show",
        "drivers/tty/serial/serial_core.c:closing_wait_show",
        "drivers/tty/serial/serial_core.c:close_delay_show",
        "drivers/tty/serial/serial_core.c:xmit_fifo_size_show",
        "drivers/tty/serial/serial_core.c:flags_show",
        "drivers/tty/serial/serial_core.c:irq_show",
        "drivers/tty/serial/serial_core.c:port_show",
        "drivers/tty/serial/serial_core.c:line_show",
        "drivers/tty/serial/serial_core.c:type_show",
        "drivers/tty/serial/serial_core.c:uartclk_show",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590447584,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498531936,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498531936,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231181068,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231181068,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291746688,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291746688,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276150746,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276150746,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585571936,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571936,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437136,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437136,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585761344,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585761344,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int uart_get_info(struct tty_port * port, struct serial_struct * retinfo)
```

```json
{
  "name": "uart_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869568,
      "name": "uart_get_info",
      "external": false,
      "loc": "drivers/tty/serial/serial_core.c:754",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift",
        "drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base",
        "drivers/tty/serial/serial_core.c:uart_get_attr_io_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor",
        "drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait",
        "drivers/tty/serial/serial_core.c:uart_get_attr_close_delay",
        "drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size",
        "drivers/tty/serial/serial_core.c:uart_get_attr_flags",
        "drivers/tty/serial/serial_core.c:uart_get_attr_irq",
        "drivers/tty/serial/serial_core.c:uart_get_attr_port",
        "drivers/tty/serial/serial_core.c:uart_get_attr_line",
        "drivers/tty/serial/serial_core.c:uart_get_attr_type",
        "drivers/tty/serial/serial_core.c:uart_get_attr_uartclk",
        "drivers/tty/serial/serial_core.c:uart_get_info_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869568,
      "name": "uart_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
