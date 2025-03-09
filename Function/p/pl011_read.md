# Function: <code>pl011_read</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
unsigned int pl011_read(const struct uart_amba_port * uap, unsigned int reg)
```

```json
{
  "name": "pl011_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498624224,
      "name": "pl011_read",
      "external": false,
      "loc": "drivers/tty/serial/amba-pl011.c:289",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_putchar",
        "drivers/tty/serial/amba-pl011.c:pl011_set_termios",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown_channel",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_put_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_break_ctl",
        "drivers/tty/serial/amba-pl011.c:pl011_set_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_get_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_empty",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_char",
        "drivers/tty/serial/amba-pl011.c:pl011_start_tx",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498624224,
      "name": "pl011_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pl011_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243856852,
      "name": "pl011_read",
      "external": false,
      "loc": "drivers/tty/serial/amba-pl011.c:289",
      "file": "drivers/tty/serial/amba-pl011.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_setup",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_write",
        "drivers/tty/serial/amba-pl011.c:pl011_console_putchar",
        "drivers/tty/serial/amba-pl011.c:pl011_set_termios",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_enable_interrupts",
        "drivers/tty/serial/amba-pl011.c:pl011_put_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_get_poll_char",
        "drivers/tty/serial/amba-pl011.c:pl011_break_ctl",
        "drivers/tty/serial/amba-pl011.c:pl011_set_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_get_mctrl",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_empty",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_int",
        "drivers/tty/serial/amba-pl011.c:pl011_tx_char",
        "drivers/tty/serial/amba-pl011.c:pl011_start_tx",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty",
        "drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty"
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
unsigned int pl011_read(const struct uart_amba_port * uap, unsigned int reg)
```
</details>
</li>
</ul>
