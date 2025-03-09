# Function: <code>__pm_runtime_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445136,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:919",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_post_runtime_resume",
        "drivers/tty/serial/8250/8250_port.c:serial8250_rpm_put_tx",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_put_card"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445136,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584781088,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:919",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_runtime_active",
        "block/blk-core.c:blk_post_runtime_resume",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584781088,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972512,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:996",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_runtime_active",
        "block/blk-core.c:blk_post_runtime_resume",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972512,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058128,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:996",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_runtime_active",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058128,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585480976,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:997",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_runtime_active",
        "drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585480976,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585726080,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:997",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_set_runtime_active",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726080,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585858176,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1004",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_set_runtime_active",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585858176,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586095552,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1033",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_set_runtime_active",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586095552,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586243104,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586243104,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587011280,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011280,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587096016,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1065",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587096016,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982320,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1065",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:spi_set_cs_timing",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982320,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587548336,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1084",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548336,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588880144,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1109",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_post_runtime_resume",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880144,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590388480,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1122",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_post_runtime_resume",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388480,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590708208,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1122",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_post_runtime_resume",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590708208,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591070064,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1123",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/serial_core.c:__uart_start",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_startup",
        "drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char",
        "drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty",
        "drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq",
        "drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx",
        "drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep",
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:spi_setup",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_unbind_device",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591070064,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499059928,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499059928,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231613108,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_config_rs485",
        "drivers/tty/serial/omap-serial.c:serial_omap_console_write",
        "drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char",
        "drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char",
        "drivers/tty/serial/omap-serial.c:serial_omap_pm",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_termios",
        "drivers/tty/serial/omap-serial.c:serial_omap_shutdown",
        "drivers/tty/serial/omap-serial.c:serial_omap_break_ctl",
        "drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl",
        "drivers/tty/serial/omap-serial.c:serial_omap_get_mctrl",
        "drivers/tty/serial/omap-serial.c:serial_omap_tx_empty",
        "drivers/tty/serial/omap-serial.c:serial_omap_irq",
        "drivers/tty/serial/omap-serial.c:serial_omap_unthrottle",
        "drivers/tty/serial/omap-serial.c:serial_omap_throttle",
        "drivers/tty/serial/omap-serial.c:serial_omap_start_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_rx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_enable_ms",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_close",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_autosuspend_device",
        "drivers/usb/musb/musb_core.c:musb_resume",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_stop",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_start",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_work",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_queue",
        "drivers/usb/musb/musb_debugfs.c:musb_softconnect_write",
        "drivers/usb/musb/musb_debugfs.c:musb_softconnect_show",
        "drivers/usb/musb/musb_debugfs.c:musb_test_mode_write",
        "drivers/usb/musb/musb_debugfs.c:musb_test_mode_show",
        "drivers/usb/musb/musb_debugfs.c:musb_regdump_show",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common",
        "drivers/power/avs/smartreflex.c:sr_disable",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:mmc_regs_show",
        "sound/soc/soc-pcm.c:soc_pcm_close",
        "sound/soc/soc-pcm.c:soc_pcm_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231613108,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292234336,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292234336,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276416520,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276416520,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586003312,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586003312,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585852448,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585852448,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586193120,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586193120,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __pm_runtime_suspend(struct device * dev, int rpmflags)
```

```json
{
  "name": "__pm_runtime_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586299376,
      "name": "__pm_runtime_suspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1035",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/core/driver.c:usb_runtime_idle",
        "drivers/usb/core/driver.c:usb_unbind_interface",
        "drivers/usb/core/driver.c:usb_probe_interface",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/mmc/core/core.c:mmc_put_card",
        "drivers/mmc/core/core.c:mmc_release_host",
        "drivers/mmc/core/core.c:mmc_release_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586299376,
      "name": "__pm_runtime_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
