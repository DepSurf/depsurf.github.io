# Function: <code>__tty_insert_flip_string_flags</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
size_t __tty_insert_flip_string_flags(struct tty_port * port, const u8 * chars, const u8 * flags, bool mutable_flags, size_t size)
```

```json
{
  "name": "__tty_insert_flip_string_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tty_insert_flip_string_flags",
      "external": true,
      "loc": "drivers/tty/tty_buffer.c:299",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer",
        "drivers/tty/vt/keyboard.c:fn_send_intr",
        "drivers/tty/vt/keyboard.c:puts_queue",
        "drivers/tty/vt/keyboard.c:put_queue",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:mouse_report",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/serial_core.c:uart_insert_char",
        "drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete",
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver",
        "drivers/usb/host/xhci-dbgtty.c:dbc_rx_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597669664,
      "name": "__tty_insert_flip_string_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071590320704,
      "name": "__tty_insert_flip_string_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
size_t __tty_insert_flip_string_flags(struct tty_port * port, const u8 * chars, const u8 * flags, bool mutable_flags, size_t size)
```
</details>
</li>
</ul>
