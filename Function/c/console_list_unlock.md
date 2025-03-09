# Function: <code>console_list_unlock</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void console_list_unlock()
```

```json
{
  "name": "console_list_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627778006,
      "name": "console_list_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:273",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop"
      ],
      "caller_func": [
        "fs/proc/consoles.c:c_stop",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/serial_core.c:uart_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/serial_core.c:console_show",
        "drivers/tty/serial/serial_core.c:uart_poll_init",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472304,
      "name": "console_list_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void console_list_unlock()
```

```json
{
  "name": "console_list_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619540886,
      "name": "console_list_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:275",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop"
      ],
      "caller_func": [
        "fs/proc/consoles.c:c_stop",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/serial_core.c:console_show",
        "drivers/tty/serial/serial_core.c:uart_poll_init",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543936,
      "name": "console_list_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void console_list_unlock()
```

```json
{
  "name": "console_list_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621839782,
      "name": "console_list_unlock",
      "external": true,
      "loc": "kernel/printk/printk.c:269",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:printk_late_init",
        "kernel/printk/printk.c:unregister_console",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:suspend_console"
      ],
      "caller_func": [
        "fs/proc/consoles.c:c_stop",
        "drivers/tty/tty_io.c:show_cons_active",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/tty/hvc/hvc_console.c:hvc_instantiate",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/tty/serial/serial_core.c:serial_core_add_one_port",
        "drivers/tty/serial/serial_core.c:console_store",
        "drivers/tty/serial/serial_core.c:console_show",
        "drivers/tty/serial/serial_core.c:uart_poll_init",
        "drivers/tty/serial/earlycon.c:setup_earlycon",
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_scrub_function",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb",
        "drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605824,
      "name": "console_list_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void console_list_unlock()
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
