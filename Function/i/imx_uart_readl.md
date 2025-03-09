# Function: <code>imx_uart_readl</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u32 imx_uart_readl(struct imx_port * sport, u32 offset)
```

```json
{
  "name": "imx_uart_readl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498651284,
      "name": "imx_uart_readl",
      "external": false,
      "loc": "drivers/tty/serial/imx.c:308",
      "file": "drivers/tty/serial/imx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_early_putchar",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_break_ctl",
        "drivers/tty/serial/imx.c:imx_uart_set_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_tx_empty",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback",
        "drivers/tty/serial/imx.c:imx_uart_stop_rx",
        "drivers/tty/serial/imx.c:imx_uart_start_rx"
      ],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_putchar",
        "drivers/tty/serial/imx.c:imx_uart_rs485_config",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_set_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_set_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_stop_rx",
        "drivers/tty/serial/imx.c:imx_uart_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498655952,
      "name": "imx_uart_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
u32 imx_uart_readl(struct imx_port * sport, u32 offset)
```

```json
{
  "name": "imx_uart_readl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231277212,
      "name": "imx_uart_readl",
      "external": false,
      "loc": "drivers/tty/serial/imx.c:308",
      "file": "drivers/tty/serial/imx.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_resume",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_suspend",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_probe",
        "drivers/tty/serial/imx.c:imx_uart_console_early_putchar",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_rs485_config",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_put_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_get_char",
        "drivers/tty/serial/imx.c:imx_uart_poll_get_char",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback",
        "drivers/tty/serial/imx.c:imx_uart_break_ctl",
        "drivers/tty/serial/imx.c:imx_uart_set_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_set_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_tx_empty",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_get_hwmctrl",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback",
        "drivers/tty/serial/imx.c:imx_uart_stop_rx",
        "drivers/tty/serial/imx.c:imx_uart_stop_rx",
        "drivers/tty/serial/imx.c:imx_uart_start_rx",
        "drivers/tty/serial/imx.c:imx_uart_start_rx"
      ],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_suspend_noirq",
        "drivers/tty/serial/imx.c:imx_uart_console_setup",
        "drivers/tty/serial/imx.c:imx_uart_console_write",
        "drivers/tty/serial/imx.c:imx_uart_console_putchar",
        "drivers/tty/serial/imx.c:imx_uart_rs485_config",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_flush_buffer",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_set_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_set_mctrl",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_stop_rx",
        "drivers/tty/serial/imx.c:imx_uart_start_rx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231273052,
      "name": "imx_uart_readl.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3231273112,
      "name": "imx_uart_readl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u32 imx_uart_readl(struct imx_port * sport, u32 offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 imx_uart_readl(struct imx_port * sport, u32 offset)
```
</details>
</li>
</ul>
